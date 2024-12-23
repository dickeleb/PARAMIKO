# PARAMIKO
Paramiko is a pure-Python 1 (3.6+) implementation of the SSHv2 protocol 2, providing both client and server functionality. It provides the foundation for the high-level SSH library Fabric, which is what we recommend you use for common client use-cases such as running remote shell commands or transferring files.

Direct use of Paramiko itself is only intended for users who need advanced/low-level primitives or want to run an in-Python sshd.

For installation information, changelogs, FAQs and similar, please visit our main project website; for API details, see the versioned docs. Additionally, the project maintainer keeps a roadmap on his personal site.

1

    Paramiko relies on cryptography for crypto functionality, which makes use of C and Rust extensions but has many precompiled options available. See our installation page for details.
2

    OpenSSH’s RFC specification page is a fantastic resource and collection of links that we won’t bother replicating here: https://www.openssh.com/specs.html

    OpenSSH itself also happens to be our primary reference implementation: when in doubt, we consult how they do things, unless there are good reasons not to. There are always some gaps, but we do our best to reconcile them when possible.

