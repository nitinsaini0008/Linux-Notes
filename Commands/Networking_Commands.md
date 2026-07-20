# Networking Commands

## About

This file contains the most commonly used Linux networking commands. These commands are essential for Network Engineers, System Administrators, and Cyber Security Professionals.

---

# 1. ip addr

## Purpose

Displays all network interfaces and their IP addresses.

## Syntax

```bash
ip addr
```

## Example

```bash
ip addr
```

---

# 2. ifconfig

## Purpose

Displays or configures network interfaces.

## Syntax

```bash
ifconfig
```

## Example

```bash
ifconfig
```

> Note: `ifconfig` is deprecated on many Linux distributions. Use `ip addr` instead.

---

# 3. ping

## Purpose

Tests connectivity between two devices.

## Syntax

```bash
ping hostname
```

## Example

```bash
ping google.com
```

Stop ping using:

```bash
Ctrl + C
```

---

# 4. traceroute

## Purpose

Shows the path packets take to reach the destination.

## Syntax

```bash
traceroute hostname
```

## Example

```bash
traceroute google.com
```

---

# 5. hostname

## Purpose

Displays the system hostname.

## Syntax

```bash
hostname
```

Example

```bash
hostname
```

---

# 6. hostnamectl

## Purpose

Displays and changes the system hostname.

## Syntax

```bash
hostnamectl
```

Change hostname

```bash
sudo hostnamectl set-hostname Kali-PC
```

---

# 7. netstat

## Purpose

Displays active network connections.

## Syntax

```bash
netstat -a
```

Useful Options

```bash
netstat -tuln
```

---

# 8. ss

## Purpose

Displays socket statistics.

## Syntax

```bash
ss
```

Example

```bash
ss -tuln
```

---

# 9. nslookup

## Purpose

Queries DNS records.

## Syntax

```bash
nslookup domain.com
```

Example

```bash
nslookup google.com
```

---

# 10. dig

## Purpose

Displays detailed DNS information.

## Syntax

```bash
dig google.com
```

---

# 11. curl

## Purpose

Transfers data from a server.

## Syntax

```bash
curl URL
```

Example

```bash
curl https://google.com
```

---

# 12. wget

## Purpose

Downloads files from the internet.

## Syntax

```bash
wget URL
```

Example

```bash
wget https://example.com/file.zip
```

---

# 13. arp

## Purpose

Displays the ARP table.

## Syntax

```bash
arp -a
```

---

# 14. route

## Purpose

Displays the routing table.

## Syntax

```bash
route -n
```

---

# 15. ip route

## Purpose

Displays the routing table using the ip command.

## Syntax

```bash
ip route
```

---

# 16. ssh

## Purpose

Connects securely to a remote Linux server.

## Syntax

```bash
ssh username@ip_address
```

Example

```bash
ssh nitin@192.168.1.10
```

---

# 17. scp

## Purpose

Copies files securely between two systems.

## Syntax

```bash
scp file.txt username@ip:/home/user
```

---

# 18. ftp

## Purpose

Connects to an FTP server.

## Syntax

```bash
ftp server_ip
```

---

# Interview Questions

1. Difference between ping and traceroute.
2. What is the purpose of ip addr?
3. Difference between netstat and ss.
4. What is DNS lookup?
5. Why is ifconfig deprecated?
6. What is SSH?
7. Difference between wget and curl?
8. What is the use of scp?

---

# Summary

Commands Covered

- ip addr
- ifconfig
- ping
- traceroute
- hostname
- hostnamectl
- netstat
- ss
- nslookup
- dig
- curl
- wget
- arp
- route
- ip route
- ssh
- scp
- ftp

Total Commands: 18

**End of File**
