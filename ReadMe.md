# SSH 

## SSH? What is this?

The SSH protocol (also referred to as Secure Shell) is a method for secure remote login from one computer to another. It provides several alternative options for strong authentication, and it protects the communications security and integrity with strong encryption. It is a secure alternative to the non-protected login protocols (such as telnet, rlogin) and insecure file transfer methods (such as FTP).

## How does it work ?

The protocol works in the client-server model, which means that the connection is established by the SSH client connecting to the SSH server. The SSH client drives the connection setup process and uses public key cryptography to verify the identity of the SSH server. After the setup phase the SSH protocol uses strong symmetric encryption and hashing algorithms to ensure the privacy and integrity of the data that is exchanged between the client and server.

## What are the use case ?

The protocol is used in corporate networks for:

-providing secure access for users and automated processes
-interactive and automated file transfers
-issuing remote commands
-managing network infrastructure and other mission-critical system components.

## How to generate one

### For Windows 

Install Git for Windows wich is avaible [here](https://gitforwindows.org/), then 

```shell
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```