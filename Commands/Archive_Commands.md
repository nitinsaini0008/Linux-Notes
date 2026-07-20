# Archive & Compression Commands

## About

This file contains Linux archive and compression commands. These commands are used to compress, extract, archive, and reduce file size for backup and transfer purposes.

---

# 1. tar

## Purpose

Creates and extracts archive files.

## Syntax

Create Archive

```bash
tar -cvf archive.tar folder/
```

Extract Archive

```bash
tar -xvf archive.tar
```

List Archive Content

```bash
tar -tvf archive.tar
```

---

# 2. gzip

## Purpose

Compresses a file using Gzip.

## Syntax

```bash
gzip filename
```

Example

```bash
gzip notes.txt
```

Output

```text
notes.txt.gz
```

---

# 3. gunzip

## Purpose

Extracts a Gzip compressed file.

## Syntax

```bash
gunzip filename.gz
```

Example

```bash
gunzip notes.txt.gz
```

---

# 4. zip

## Purpose

Compresses files into ZIP format.

## Syntax

```bash
zip archive.zip file.txt
```

Compress Folder

```bash
zip -r backup.zip Documents/
```

---

# 5. unzip

## Purpose

Extracts ZIP archives.

## Syntax

```bash
unzip archive.zip
```

Example

```bash
unzip backup.zip
```

---

# 6. bzip2

## Purpose

Compresses files using the Bzip2 algorithm.

## Syntax

```bash
bzip2 filename
```

Example

```bash
bzip2 report.txt
```

---

# 7. bunzip2

## Purpose

Extracts Bzip2 compressed files.

## Syntax

```bash
bunzip2 filename.bz2
```

---

# 8. xz

## Purpose

Compresses files using the XZ algorithm.

## Syntax

```bash
xz filename
```

Example

```bash
xz notes.txt
```

---

# 9. unxz

## Purpose

Extracts XZ compressed files.

## Syntax

```bash
unxz filename.xz
```

---

# 10. tar with gzip

## Purpose

Creates a compressed tar archive.

## Syntax

Create

```bash
tar -czvf backup.tar.gz folder/
```

Extract

```bash
tar -xzvf backup.tar.gz
```

---

# 11. tar with bzip2

## Syntax

Create

```bash
tar -cjvf backup.tar.bz2 folder/
```

Extract

```bash
tar -xjvf backup.tar.bz2
```

---

# 12. tar with xz

## Syntax

Create

```bash
tar -cJvf backup.tar.xz folder/
```

Extract

```bash
tar -xJvf backup.tar.xz
```

---

# Common Archive Formats

| Format | Extension |
|---------|-----------|
| TAR | .tar |
| Gzip | .gz |
| ZIP | .zip |
| Bzip2 | .bz2 |
| XZ | .xz |
| TAR + Gzip | .tar.gz |
| TAR + Bzip2 | .tar.bz2 |
| TAR + XZ | .tar.xz |

---

# Interview Questions

1. What is the purpose of tar?
2. Difference between tar and zip?
3. What is gzip?
4. Difference between gzip and bzip2?
5. What is xz compression?
6. How do you create a tar.gz archive?
7. How do you extract a ZIP file?
8. Which compression method provides the highest compression ratio?
9. Why do we compress files?
10. What is the difference between archive and compression?

---

# Summary

Commands Covered

- tar
- gzip
- gunzip
- zip
- unzip
- bzip2
- bunzip2
- xz
- unxz

Topics Covered

- Archive Creation
- File Compression
- Archive Extraction
- Backup Files
- Compression Formats

**End of File**
