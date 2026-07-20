# File Permissions

## About

This file contains Linux file permission commands used to control access to files and directories.

---

# 1. chmod

## Purpose

The `chmod` command is used to change file or directory permissions.

## Syntax

```bash
chmod permissions filename
```

## Example

```bash
chmod 777 test.txt
```

```bash
chmod 755 script.sh
```

```bash
chmod +x script.sh
```

## Common Permission Values

| Permission | Meaning |
|------------|---------|
| 777 | Full permission for everyone |
| 755 | Owner has full access, others can read and execute |
| 700 | Only owner has full access |
| 644 | Owner can read/write, others can only read |

---

# 2. chown

## Purpose

Changes the owner of a file or directory.

## Syntax

```bash
sudo chown owner filename
```

## Example

```bash
sudo chown nitin notes.txt
```

Change owner and group

```bash
sudo chown nitin:developers notes.txt
```

---

# 3. chgrp

## Purpose

Changes the group ownership.

## Syntax

```bash
sudo chgrp groupname filename
```

## Example

```bash
sudo chgrp developers notes.txt
```

---

# 4. umask

## Purpose

Displays or changes the default permission of newly created files.

## Syntax

```bash
umask
```

## Example

```bash
umask
```

Output

```text
0022
```

Change umask

```bash
umask 002
```

---

# Understanding rwx Permissions

| Symbol | Meaning |
|--------|---------|
| r | Read |
| w | Write |
| x | Execute |
| - | No Permission |

Example

```text
-rwxr-xr-x
```

Explanation

- Owner → rwx
- Group → r-x
- Others → r-x

---

# Numeric Permission Table

| Number | Permission |
|---------|------------|
| 0 | --- |
| 1 | --x |
| 2 | -w- |
| 3 | -wx |
| 4 | r-- |
| 5 | r-x |
| 6 | rw- |
| 7 | rwx |

---

# Useful Examples

Give execute permission

```bash
chmod +x file.sh
```

Remove write permission

```bash
chmod -w file.txt
```

Read-only file

```bash
chmod 444 file.txt
```

Owner full access only

```bash
chmod 700 confidential.txt
```

---

# Interview Questions

1. What is chmod?
2. What is the difference between chown and chmod?
3. Explain permission 777.
4. Explain permission 755.
5. What does rwxr-xr-x mean?
6. What is umask?
7. What is execute permission?
8. What is the purpose of chgrp?

---

# Summary

Commands Covered

- chmod
- chown
- chgrp
- umask

Topics Covered

- rwx Permissions
- Numeric Permissions
- Ownership
- Groups
- Default Permissions

**End of File**
