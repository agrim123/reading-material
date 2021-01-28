# Port Forwarding

## Local Port Forwarding

It allows you to forward a port on the local (ssh client) machine to a port on the remote (ssh server) machine, which is then forwarded to a port on the destination machine.

```bash
$ ssh -L <local-ip>:<local-port>:<remote-ip>:<remote-port> <user>@<ssh-server>
```

## Remote Port Forwarding

It allows you to forward a port on the remote (ssh server) machine to a port on the local (ssh client) machine, which is then forwarded to a port on the destination machine.

```bash
$ ssh -R <remote-ip>:<remote-port>:<destination-ip>:<destination-port> <user>@<ssh-server>
```

## Dynamic Port Forwarding

All the applications using the SOCKS proxy will connect to the SSH server, and the server will forward all the traffic to its actual destination.

```bash
$ ssh -g -f -N -D <local-port> <user>@<host>
```

## Tunnel all traffic to a subnet

```bash
$ sshuttle -r <user>@<host> 0.0.0.0/0
```

## Proxy DNS traffic

```bash
$ sshuttle --dns -r <user>@<host> 0.0.0.0/0
```