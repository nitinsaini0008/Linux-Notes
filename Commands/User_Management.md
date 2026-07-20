# User Management

## About

This file contains Linux user management commands.

---

# 1. whoami

## Purpose

Displays the currently logged-in user.

## Syntax

```bash
whoami
```

## Example

```bash
whoami
```

## Output

```text
nitin
```

---

# 2. id

## Purpose

Displays user ID, group ID and group information.

## Syntax

```bash
id
```

## Example

```bash
id
```

## Output

```text
uid=1000(nitin) gid=1000(nitin) groups=1000(nitin)
```

---

# 3. passwd

## Purpose

Changes the password of a user.

## Syntax

```bash
passwd
```

Change another user's password

```bash
sudo passwd username
```

---

# 4. useradd

## Purpose

Creates a new user.

## Syntax

```bash
sudo useradd username
```

## Example

```bash
sudo useradd rahul
```

---

# 5. usermod

## Purpose

Modify an existing user.

## Syntax

```bash
sudo usermod options username
```

Example

```bash
sudo usermod -aG sudo rahul
```

Add user to sudo group.

---

# 6. userdel

## Purpose

Delete a user.

## Syntax

```bash
sudo userdel username
```

Example

```bash
sudo userdel rahul
```

Delete user with home directory

```bash
sudo userdel -r rahul
```

---

# 7. groupadd

## Purpose

Create a new group.

## Syntax

```bash
sudo groupadd developers
```

---

# 8. groupdel

## Purpose

Delete a group.

## Syntax

```bash
sudo groupdel developers
```

---

# 9. groups

## Purpose

Shows groups of current user.

## Syntax

```bash
groups
```

Example Output

```text
nitin sudo adm
```

---

# 10. sudo

## Purpose

Run commands as Administrator.

## Syntax

```bash
sudo command
```

Example

```bash
sudo apt update
```

---

# 11. su

## Purpose

Switch another user.

## Syntax

```bash
su username
```

Switch to root

```bash
su root
```

---

# 12. exit

## Purpose

Exit current user session.

## Syntax

```bash
exit
```

---

# Practice

Create user

```bash
sudo useradd testuser
```

Set password

```bash
sudo passwd testuser
```

Check user

```bash
id testuser
```

Delete user

```bash
sudo userdel -r testuser
```

---

# Interview Questions

1. Difference between useradd and adduser?
2. What is sudo?
3. Difference between su and sudo?
4. What does id command display?
5. How do you delete a user with home directory?
6. How do you change a user's password?
7. What is the purpose of groups command?
8. How do you add a user to the sudo group?

---

# Summary

Commands Covered

- whoami
- id
- passwd
- useradd
- usermod
- userdel
- groupadd
- groupdel
- groups
- sudo
- su
- exit

Total Commands: 12
