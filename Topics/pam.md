# Pluggable Authentication Modules

- Programs that grant users access to a system use authentication to verify each other's identity (that is, to establish that a user is who they say they are).
- The problem is that every time a new authentication scheme is developed, it requires all necessary programs to be rewritten to support it. PAM provides ay to develop programs that are independent of authentication scheme.

## Configuration Files

- `/etc/pam.d/` contains all PAM configuration files.
- Linux-PAM deals with four separate types of (management) task.
    - authentication management
    - account management
    - session management
    - password management.
- The association of the preferred management scheme with the behavior of an application is made with entries in the relevant Linux-PAM configuration file. The management functions are performed by modules specified in the configuration file.

### Syntax

The format of each rule is a space separated collection of tokens, the first three being case-insensitive:

```vim
type control module-path module-arguments
```

## References

- [Linux PAM Guides](http://www.linux-pam.org/Linux-PAM-html/)
