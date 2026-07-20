# File Commands

## About
 
This file contains all basic Linux file management commands.

---

# 1. pwd

## Purpose

Displays the current working directory.

## Syntax

```bash
pwd
```

## Example

```bash
pwd
```

## Output

```text
/home/nitin
```

## Practical Use

Used to check your current location in Linux.

---

# 2. ls

## Purpose

Lists files and folders.

## Syntax

```bash
ls
```

## Example

```bash
ls
```

## Output

```text
Desktop
Documents
Downloads
Pictures
Videos
```

## Useful Options

```bash
ls -l
```

Long listing

```bash
ls -a
```

Show hidden files

```bash
ls -lh
```

Human readable size

```bash
ls -la
```

Long listing with hidden files

---

# 3. cd

## Purpose

Change current directory.

## Syntax

```bash
cd FolderName
```

## Example

```bash
cd Downloads
```

Go Back

```bash
cd ..
```

Go Home

```bash
cd ~
```

---

# 4. mkdir

## Purpose

Create a new directory.

## Syntax

```bash
mkdir FolderName
```

## Example

```bash
mkdir Linux
```

Create Multiple Directories

```bash
mkdir Notes Practice Assignments
```

---

# 5. rmdir

## Purpose

Remove an empty directory.

## Syntax

```bash
rmdir FolderName
```

## Example

```bash
rmdir Linux
```

---

# 6. touch

## Purpose

Create an empty file.

## Syntax

```bash
touch filename
```

## Example

```bash
touch notes.txt
```

Multiple Files

```bash
touch file1.txt file2.txt file3.txt
```

---

# 7. cp

## Purpose

Copy files.

## Syntax

```bash
cp source destination
```

## Example

```bash
cp notes.txt backup.txt
```

Copy Folder

```bash
cp -r Linux Backup
```

---

# 8. mv

## Purpose

Move or rename files.

## Syntax

```bash
mv source destination
```

Rename File

```bash
mv file1.txt file2.txt
```

Move File

```bash
mv notes.txt Documents/
```

---

# 9. rm

## Purpose

Delete files.

## Syntax

```bash
rm filename
```

## Example

```bash
rm notes.txt
```

Delete Folder

```bash
rm -r Linux
```

Warning

Be careful while using rm because deleted files cannot be recovered easily.

---

# 10. cat

## Purpose

Display file contents.

## Syntax

```bash
cat filename
```

## Example

```bash
cat notes.txt
```

---

# 11. head

## Purpose

Show first 10 lines of a file.

## Syntax

```bash
head filename
```

## Example

```bash
head notes.txt
```

---

# 12. tail

## Purpose

Show last 10 lines of a file.

## Syntax

```bash
tail filename
```

## Example

```bash
tail notes.txt
```

---

# 13. less

## Purpose

Read large files page by page.

## Syntax

```bash
less filename
```

## Example

```bash
less notes.txt
```


# Interview Questions

1. What is the difference between cp and mv?
2. What is the use of pwd?
3. What is the difference between rm and rmdir?
4. What does ls -la do?
5. What is the purpose of touch command?

---

**End of File**
