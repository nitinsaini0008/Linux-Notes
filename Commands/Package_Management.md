# Package Management

## About

This file contains Linux package management commands used to install, update, remove, and manage software packages in different Linux distributions.

---

# 1. apt

## Purpose

APT (Advanced Package Tool) is used in Debian and Ubuntu-based Linux distributions.

## Update Package List

```bash
sudo apt update
```

## Upgrade Installed Packages

```bash
sudo apt upgrade
```

## Install a Package

```bash
sudo apt install package_name
```

Example

```bash
sudo apt install git
```

## Remove a Package

```bash
sudo apt remove package_name
```

Example

```bash
sudo apt remove git
```

## Remove Package with Configuration Files

```bash
sudo apt purge package_name
```

## Remove Unused Packages

```bash
sudo apt autoremove
```

---

# 2. yum

## Purpose

YUM (Yellowdog Updater Modified) is used in CentOS and older Red Hat systems.

## Install Package

```bash
sudo yum install package_name
```

Example

```bash
sudo yum install httpd
```

## Update Packages

```bash
sudo yum update
```

## Remove Package

```bash
sudo yum remove package_name
```

---

# 3. dnf

## Purpose

DNF is the default package manager in modern Fedora and Red Hat Enterprise Linux.

## Install Package

```bash
sudo dnf install package_name
```

Example

```bash
sudo dnf install nginx
```

## Update Packages

```bash
sudo dnf update
```

## Remove Package

```bash
sudo dnf remove package_name
```

---

# 4. rpm

## Purpose

RPM is used to install and manage RPM package files.

## Install RPM Package

```bash
sudo rpm -ivh package.rpm
```

## Upgrade RPM Package

```bash
sudo rpm -Uvh package.rpm
```

## Remove RPM Package

```bash
sudo rpm -e package_name
```

## List Installed RPM Packages

```bash
rpm -qa
```

---

# 5. dpkg

## Purpose

DPKG manages Debian package (.deb) files.

## Install Package

```bash
sudo dpkg -i package.deb
```

## Remove Package

```bash
sudo dpkg -r package_name
```

## List Installed Packages

```bash
dpkg -l
```

---

# Package Cache Commands

Clean Cache

```bash
sudo apt clean
```

Remove Old Cache

```bash
sudo apt autoclean
```

---

# Check Installed Package

Ubuntu

```bash
apt list --installed
```

Red Hat

```bash
rpm -qa
```

---

# Search Package

Ubuntu

```bash
apt search package_name
```

Example

```bash
apt search apache2
```

---

# Interview Questions

1. What is APT?
2. Difference between apt and dpkg?
3. Difference between yum and dnf?
4. What is RPM?
5. What is apt update?
6. What is apt upgrade?
7. What is apt autoremove?
8. How do you install a .deb package?
9. How do you install an RPM package?
10. Which package manager is used in Ubuntu?

---

# Summary

Package Managers Covered

- apt
- yum
- dnf
- rpm
- dpkg

Topics Covered

- Install Package
- Remove Package
- Update Package
- Upgrade Package
- Search Package
- Clean Cache

**End of File**
