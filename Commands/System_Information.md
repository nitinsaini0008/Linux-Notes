# System Information Commands

## About

This file contains Linux system information commands used to view operating system details, hardware information, memory usage, logged-in users, and system uptime.

---

# 1. hostname

## Purpose

Displays the hostname of the system.

## Syntax

```bash
hostname
```

Example

```bash
hostname
```

---

# 2. hostnamectl

## Purpose

Displays and manages system hostname information.

## Syntax

```bash
hostnamectl
```

Change Hostname

```bash
sudo hostnamectl set-hostname Kali-PC
```

---

# 3. uname

## Purpose

Displays system information.

## Syntax

```bash
uname
```

Display All Information

```bash
uname -a
```

Kernel Version

```bash
uname -r
```

---

# 4. lscpu

## Purpose

Displays CPU architecture and processor details.

## Syntax

```bash
lscpu
```

---

# 5. free

## Purpose

Displays RAM and swap memory usage.

## Syntax

```bash
free
```

Human Readable

```bash
free -h
```

---

# 6. uptime

## Purpose

Displays system running time and load average.

## Syntax

```bash
uptime
```

---

# 7. who

## Purpose

Displays currently logged-in users.

## Syntax

```bash
who
```

---

# 8. whoami

## Purpose

Displays the current logged-in username.

## Syntax

```bash
whoami
```

---

# 9. w

## Purpose

Shows logged-in users and their activities.

## Syntax

```bash
w
```

---

# 10. last

## Purpose

Displays login history.

## Syntax

```bash
last
```

---

# 11. date

## Purpose

Displays the current system date and time.

## Syntax

```bash
date
```

---

# 12. cal

## Purpose

Displays a calendar.

## Syntax

```bash
cal
```

Current Year

```bash
cal 2026
```

---

# 13. timedatectl

## Purpose

Displays and manages system date and time settings.

## Syntax

```bash
timedatectl
```

---

# 14. env

## Purpose

Displays all environment variables.

## Syntax

```bash
env
```

---

# 15. printenv

## Purpose

Displays environment variables.

## Syntax

```bash
printenv
```

---

# 16. arch

## Purpose

Displays system architecture.

## Syntax

```bash
arch
```

---

# 17. neofetch

## Purpose

Displays detailed system information in a formatted view.

## Syntax

```bash
neofetch
```

> Note: Install using `sudo apt install neofetch` if it is not installed.

---

# Interview Questions

1. What is the purpose of uname?
2. Difference between who and whoami?
3. What does uptime display?
4. How do you check RAM usage?
5. What is lscpu used for?
6. How do you check login history?
7. What is timedatectl?
8. What is the purpose of env?
9. What is printenv?
10. What does arch command display?

---

# Summary

Commands Covered

- hostname
- hostnamectl
- uname
- lscpu
- free
- uptime
- who
- whoami
- w
- last
- date
- cal
- timedatectl
- env
- printenv
- arch
- neofetch

Topics Covered

- System Information
- CPU Information
- Memory Information
- Logged-in Users
- Login History
- Date & Time
- Environment Variables

**End of File**
