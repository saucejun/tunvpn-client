# tunvpn

A minimal overlay network / VPN prototype based on Linux TUN and Java.

## Features

- Linux TUN virtual network interface
- User-space IP packet capture and injection
- JNA-based ioctl(TUNSETIFF) initialization
- Maven-managed Java project
- Designed for educational / thesis purposes

## Environment

- Linux (Ubuntu 20.04+)
- Java 17
- Maven 3.x
- Root privileges required

## Build

```bash
mvn compile