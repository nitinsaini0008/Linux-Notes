# Disk Management

## About

This file contains Linux disk management commands used to monitor storage, partitions, mounted file systems, and disk usage.

---

# 1. df

## Purpose

Displays the available and used disk space of all mounted file systems.

## Syntax

```bash
df
```

Human Readable Format

```bash
df -h
```

Example

```bash
df -h
```

---

# 2. du

## Purpose

Displays the disk usage of files and directories.

## Syntax

```bash
du
```

Human Readable Format

```bash
du -sh
```

Example

```bash
du -sh Documents
```

---

# 3. lsblk

## Purpose

Lists all available block storage devices.

## Syntax

```bash
lsblk
```

Example

```bash
lsblk
```

---

# 4. fdisk

## Purpose

Used to create, delete, and manage disk partitions.

## Syntax

```bash
sudo fdisk -l
```

List All Partitions

```bash
sudo fdisk -l
```

---

# 5. mount

## Purpose

Mounts a storage device to the Linux file system.

## Syntax

```bash
sudo mount device mount_point
```

Example

```bash
sudo mount /dev/sdb1 /mnt
```

---

# 6. umount

## Purpose

Unmounts a mounted storage device.

## Syntax

```bash
sudo umount mount_point
```

Example

```bash
sudo umount /mnt
```

---

# 7. blkid

## Purpose

Displays UUID and filesystem information.

## Syntax

```bash
sudo blkid
```

---

# 8. parted

## Purpose

Creates and manages partitions larger than 2 TB.

## Syntax

```bash
sudo parted
```

---

# 9. mkfs

## Purpose

Creates a new filesystem.

## Syntax

```bash
sudo mkfs.ext4 /dev/sdb1
```

Example

```bash
sudo mkfs.ext4 /dev/sdb1
```

---

# 10. fsck

## Purpose

Checks and repairs Linux file systems.

## Syntax

```bash
sudo fsck /dev/sdb1
```

---

# 11. free

## Purpose

Displays RAM and swap memory usage.

## Syntax

```bash
free -h
```

---

# 12. swapon

## Purpose

Enables swap memory.

## Syntax

```bash
sudo swapon /swapfile
```

---

# 13. swapoff

## Purpose

Disables swap memory.

## Syntax

```bash
sudo swapoff /swapfile
```

---

# Common Filesystem Types

| Filesystem | Description |
|------------|-------------|
| ext4 | Most common Linux filesystem |
| ext3 | Older Linux filesystem |
| xfs | High-performance filesystem |
| btrfs | Modern Linux filesystem |
| FAT32 | Windows compatible |
| NTFS | Windows filesystem |

---

# Interview Questions

1. What is the difference between df and du?
2. What does lsblk display?
3. What is fdisk used for?
4. Difference between mount and umount?
5. What is UUID?
6. What is mkfs?
7. What is fsck?
8. What is swap memory?
9. Which filesystem is commonly used in Linux?
10. Why do we use df -h?

---

# Summary

Commands Covered

- df
- du
- lsblk
- fdisk
- mount
- umount
- blkid
- parted
- mkfs
- fsck
- free
- swapon
- swapoff

Topics Covered

- Disk Usage
- Partitions
- File Systems
- Mounting
- Swap Memory

**End of File**
