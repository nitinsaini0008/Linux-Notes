# Search Commands

## About

This file contains Linux search commands used to locate files, directories, text patterns, and executable programs.

---

# 1. find

## Purpose

Searches for files and directories in a specified location.

## Syntax

```bash
find path options
```

## Example

Search a file

```bash
find /home -name notes.txt
```

Search all .txt files

```bash
find . -name "*.txt"
```

Search directories only

```bash
find . -type d
```

Search files only

```bash
find . -type f
```

---

# 2. locate

## Purpose

Finds files using a pre-built database.

## Syntax

```bash
locate filename
```

## Example

```bash
locate passwd
```

Update Database

```bash
sudo updatedb
```

---

# 3. grep

## Purpose

Searches for specific text inside files.

## Syntax

```bash
grep "text" filename
```

## Example

```bash
grep "root" /etc/passwd
```

Ignore Case

```bash
grep -i "linux" notes.txt
```

Show Line Numbers

```bash
grep -n "error" log.txt
```

Recursive Search

```bash
grep -r "password" .
```

---

# 4. which

## Purpose

Displays the location of an executable command.

## Syntax

```bash
which command
```

## Example

```bash
which python3
```

---

# 5. whereis

## Purpose

Displays binary, source, and manual page locations.

## Syntax

```bash
whereis command
```

## Example

```bash
whereis ssh
```

---

# 6. xargs

## Purpose

Builds and executes commands from standard input.

## Syntax

```bash
command | xargs command
```

## Example

```bash
find . -name "*.txt" | xargs rm
```

---

# 7. sort

## Purpose

Sorts text alphabetically.

## Syntax

```bash
sort filename
```

## Example

```bash
sort names.txt
```

Reverse Sort

```bash
sort -r names.txt
```

---

# 8. uniq

## Purpose

Removes duplicate lines.

## Syntax

```bash
uniq filename
```

## Example

```bash
uniq names.txt
```

Count Duplicate Lines

```bash
uniq -c names.txt
```

---

# 9. wc

## Purpose

Counts lines, words, and characters.

## Syntax

```bash
wc filename
```

## Example

```bash
wc notes.txt
```

Count Lines

```bash
wc -l notes.txt
```

Count Words

```bash
wc -w notes.txt
```

Count Characters

```bash
wc -m notes.txt
```

---

# 10. diff

## Purpose

Compares two files.

## Syntax

```bash
diff file1.txt file2.txt
```

---

# 11. cmp

## Purpose

Compares two files byte by byte.

## Syntax

```bash
cmp file1.txt file2.txt
```

---

# 12. file

## Purpose

Displays the file type.

## Syntax

```bash
file filename
```

## Example

```bash
file notes.txt
```

---

# Interview Questions

1. What is the difference between find and locate?
2. What is grep used for?
3. Difference between which and whereis?
4. What does wc command do?
5. What is the use of uniq?
6. What is xargs?
7. What is diff?
8. What is the purpose of file command?
9. How do you search recursively using grep?
10. Why is updatedb required for locate?

---

# Summary

Commands Covered

- find
- locate
- grep
- which
- whereis
- xargs
- sort
- uniq
- wc
- diff
- cmp
- file

Topics Covered

- File Search
- Text Search
- File Comparison
- Sorting
- Duplicate Detection
- File Information

**End of File**
