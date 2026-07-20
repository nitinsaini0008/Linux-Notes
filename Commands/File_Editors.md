# File Editors

## About

This file contains the most commonly used Linux text editors. These editors are used to create, modify, and manage configuration files, scripts, and documents directly from the terminal.

---

# 1. nano

## Purpose

Nano is a beginner-friendly terminal text editor.

## Syntax

```bash
nano filename
```

## Example

```bash
nano notes.txt
```

### Save File

```text
Ctrl + O
```

Press

```text
Enter
```

### Exit

```text
Ctrl + X
```

---

# 2. vi

## Purpose

Vi is a powerful command-line text editor available on almost every Linux system.

## Syntax

```bash
vi filename
```

## Example

```bash
vi notes.txt
```

### Modes

| Mode | Description |
|------|-------------|
| Normal Mode | Default mode |
| Insert Mode | Write text |
| Command Mode | Save, Quit, Search |

### Enter Insert Mode

```text
Press i
```

### Save & Exit

```text
Esc
:wq
```

### Exit Without Saving

```text
Esc
:q!
```

---

# 3. vim

## Purpose

Vim (Vi Improved) is an advanced version of Vi.

## Syntax

```bash
vim filename
```

## Example

```bash
vim script.sh
```

### Save

```text
:w
```

### Save and Exit

```text
:wq
```

### Quit

```text
:q
```

### Quit Without Saving

```text
:q!
```

---

# 4. gedit

## Purpose

Gedit is a graphical text editor used in Linux desktop environments.

## Syntax

```bash
gedit filename
```

## Example

```bash
gedit notes.txt
```

Run in Background

```bash
gedit notes.txt &
```

---

# 5. cat

## Purpose

Display file contents directly in the terminal.

## Syntax

```bash
cat filename
```

Example

```bash
cat notes.txt
```

Create File

```bash
cat > notes.txt
```

Press

```text
Ctrl + D
```

to save.

---

# 6. less

## Purpose

Read large files page by page.

## Syntax

```bash
less filename
```

Exit

```text
q
```

---

# 7. more

## Purpose

Displays file contents one screen at a time.

## Syntax

```bash
more filename
```

---

# Common Shortcut Keys

| Shortcut | Purpose |
|----------|----------|
| Ctrl + O | Save (Nano) |
| Ctrl + X | Exit (Nano) |
| Ctrl + K | Cut Line (Nano) |
| Ctrl + U | Paste Line (Nano) |
| Ctrl + W | Search (Nano) |
| i | Insert Mode (Vi/Vim) |
| Esc | Exit Insert Mode |
| :w | Save |
| :q | Quit |
| :wq | Save & Quit |
| :q! | Quit Without Saving |

---

# Interview Questions

1. What is Nano?
2. Difference between Vi and Vim?
3. Which editor is beginner-friendly?
4. What is Gedit?
5. How do you save a file in Nano?
6. How do you quit Vim without saving?
7. Difference between less and more?
8. What is the use of cat command?

---

# Summary

Editors Covered

- nano
- vi
- vim
- gedit
- cat
- less
- more

Topics Covered

- File Editing
- Terminal Editors
- GUI Editors
- Keyboard Shortcuts
- Save & Exit Commands

**End of File**
