# Shell Commands

## About

This file contains commonly used Linux shell commands. These commands help users navigate the terminal, execute commands efficiently, manage command history, create aliases, and automate tasks.

---

# 1. echo

## Purpose

Displays text or variable values on the terminal.

## Syntax

```bash
echo "Hello World"
```

Example

```bash
echo "Welcome to Linux"
```

Output

```text
Welcome to Linux
```

Print Username

```bash
echo $USER
```

Print Home Directory

```bash
echo $HOME
```

---

# 2. history

## Purpose

Displays previously executed commands.

## Syntax

```bash
history
```

Run Previous Command Again

```bash
!!
```

Run Command Number

```bash
!25
```

Clear History

```bash
history -c
```

---

# 3. alias

## Purpose

Creates shortcut commands.

## Syntax

```bash
alias shortcut='command'
```

Example

```bash
alias ll='ls -la'
```

View Aliases

```bash
alias
```

Remove Alias

```bash
unalias ll
```

---

# 4. clear

## Purpose

Clears the terminal screen.

## Syntax

```bash
clear
```

Shortcut

```text
Ctrl + L
```

---

# 5. exit

## Purpose

Closes the current terminal session.

## Syntax

```bash
exit
```

---

# 6. man

## Purpose

Displays the manual page for a command.

## Syntax

```bash
man command_name
```

Example

```bash
man ls
```

Exit Manual

```text
Press q
```

---

# 7. uname

## Purpose

Displays system information.

## Syntax

```bash
uname
```

Detailed Information

```bash
uname -a
```

---

# 8. date

## Purpose

Displays the current system date and time.

## Syntax

```bash
date
```

---

# 9. cal

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

# 10. which

## Purpose

Shows the location of an executable command.

## Syntax

```bash
which command
```

Example

```bash
which python3
```

---

# 11. whereis

## Purpose

Finds the binary, source, and manual page of a command.

## Syntax

```bash
whereis command
```

Example

```bash
whereis ssh
```

---

# 12. who

## Purpose

Displays users currently logged into the system.

## Syntax

```bash
who
```

---

# 13. uptime

## Purpose

Shows how long the system has been running.

## Syntax

```bash
uptime
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

# Interview Questions

1. What is the purpose of the echo command?
2. What is the difference between which and whereis?
3. What does history command do?
4. How do you create an alias?
5. What is the use of uname?
6. What is the purpose of env?
7. How do you clear the terminal?
8. How do you close the terminal?
9. What is the use of man command?
10. What does uptime display?

---

# Summary

Commands Covered

- echo
- history
- alias
- unalias
- clear
- exit
- man
- uname
- date
- cal
- which
- whereis
- who
- uptime
- env

Topics Covered

- Terminal Basics
- Environment Variables
- Command History
- Aliases
- System Information
- User Information

**End of File**
