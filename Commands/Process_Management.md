# Process Management

## About

This file contains Linux process management commands. These commands are used to monitor, control, and terminate running processes.

---

# 1. ps

## Purpose

Displays currently running processes.

## Syntax

```bash
ps
```

Show all running processes

```bash
ps -e
```

Detailed information

```bash
ps -ef
```

---

# 2. top

## Purpose

Displays real-time system resource usage.

## Syntax

```bash
top
```

Exit

```text
Press q
```

---

# 3. htop

## Purpose

Advanced interactive process viewer.

## Syntax

```bash
htop
```

> Note: Install using `sudo apt install htop` if not available.

---

# 4. kill

## Purpose

Terminates a running process using its Process ID (PID).

## Syntax

```bash
kill PID
```

Example

```bash
kill 1250
```

Force Kill

```bash
kill -9 1250
```

---

# 5. killall

## Purpose

Terminates all processes with the specified name.

## Syntax

```bash
killall process_name
```

Example

```bash
killall firefox
```

---

# 6. jobs

## Purpose

Displays background jobs in the current shell.

## Syntax

```bash
jobs
```

---

# 7. bg

## Purpose

Resumes a stopped job in the background.

## Syntax

```bash
bg
```

---

# 8. fg

## Purpose

Brings a background job to the foreground.

## Syntax

```bash
fg
```

---

# 9. nice

## Purpose

Starts a process with a specific priority.

## Syntax

```bash
nice -n 10 command
```

Example

```bash
nice -n 10 firefox
```

---

# 10. renice

## Purpose

Changes the priority of a running process.

## Syntax

```bash
renice priority PID
```

Example

```bash
sudo renice 5 1234
```

---

# 11. pidof

## Purpose

Displays the Process ID (PID) of a running program.

## Syntax

```bash
pidof process_name
```

Example

```bash
pidof sshd
```

---

# 12. pgrep

## Purpose

Searches for processes by name.

## Syntax

```bash
pgrep process_name
```

Example

```bash
pgrep firefox
```

---

# Process States

| State | Meaning |
|--------|---------|
| R | Running |
| S | Sleeping |
| D | Waiting |
| T | Stopped |
| Z | Zombie |

---

# Interview Questions

1. What is a process?
2. Difference between program and process?
3. Difference between kill and killall?
4. What is PID?
5. What is the purpose of top?
6. What is htop?
7. Difference between bg and fg?
8. What is a Zombie Process?
9. What is process priority?
10. Difference between nice and renice?

---

# Summary

Commands Covered

- ps
- top
- htop
- kill
- killall
- jobs
- bg
- fg
- nice
- renice
- pidof
- pgrep

Total Commands: 12

**End of File**
