# iptables

> administration tool for IPv4/IPv6 packet filtering and NAT

iptables is a user-space utility program that allows a system administrator to configure the tables provided by the Linux kernel firewall \(implemented as different Netfilter modules\) and the chains and rules it stores.

## Tables

1. **filter** \(default table\)
   * input
     * Controls behaviour of all incoming connections. Example: ssh.
   * forward
     * used for incoming connections that aren’t actually being delivered locally.
     * used mainly for routing, NAT, or generally for forwarding.
   * output
     * used for outgoing connections.
2. **nat** \(consulted when a packet that creates a new connection is encountered\)
   * prerouting
   * output
   * postrouting

## Allowing or denying all connections

```bash
$ iptables --policy INPUT ACCEPT
$ iptables --policy INPUT DROP
```

## Connection Specific responses

1. Accept
   * Allow the connection
2. Drop
   * Drop the connection
   * Source sees that system does not exist
3. Reject
   * Don’t allow the connection, but send back an error
   * Source sees that firewall blocked them

## Allowing / Blocking specifc connections

* configure iptables to allow or block specific addresses, address ranges, and ports.

### Connections from a single IP

Block all connections from 10.10.10.10

```bash
$ iptables -A INPUT -s 10.10.10.10 -j DROP
```

### Connections from a range of IP

Block all connections in IP range 10.10.10.0/24

```bash
$ iptables -A INPUT -s 10.10.10.0/24 -j DROP
```

### Connections to a specific port

```bash
$ iptables -A INPUT -p tcp --dport ssh -s 10.10.10.10 -j DROP
```

## Connection States

Allow ssh to your server from 10.10.10.10, but ssh to 10.10.10.10 are not permitted. However, the system is permitted to send back information over SSH as long as the session has already been established, which makes SSH communication possible between these two hosts.

```bash
$ iptables -A INPUT -p tcp --dport ssh -s 10.10.10.10 -m state --state NEW,ESTABLISHED -j ACCEPT

$ iptables -A OUTPUT -p tcp --sport 22 -d 10.10.10.10 -m state --state ESTABLISHED -j ACCEPT
```

## Saving Changes

```bash
$ sudo /sbin/iptables-save
```

## Flushing Changes

```bash
$ iptables -F
```

