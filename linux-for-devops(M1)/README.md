# 🐧 Linux for DevOps – Day 1

## 📌 Linux Basics & File System

> **Goal of Day 1**
>
> * Understand what Linux is from a DevOps perspective
> * Learn Linux directory structure
> * Practice essential file & directory commands
> * Get comfortable using the terminal

---

## 1️⃣ What is Linux? (DevOps Perspective)

Linux is an **open-source operating system** used widely in:

* Cloud servers (AWS EC2, Azure VM, GCP)
* Docker containers
* Kubernetes nodes
* CI/CD runners
* Monitoring & logging systems

📌 **Why DevOps Engineers must know Linux**

* Most production servers run Linux
* Automation scripts are written for Linux
* Containers are built on Linux OS
* Debugging issues requires Linux command knowledge

---

## 2️⃣ Linux File System Structure

Linux follows a **hierarchical directory structure**, starting from root (`/`).

| Directory  | Description                            |
| ---------- | -------------------------------------- |
| `/`        | Root directory (top of the filesystem) |
| `/home`    | Home directories for users             |
| `/root`    | Home directory for root user           |
| `/etc`     | Configuration files                    |
| `/var`     | Variable data (logs, cache, spool)     |
| `/var/log` | System & application logs              |
| `/bin`     | Essential system binaries              |
| `/usr/bin` | User-installed binaries                |
| `/tmp`     | Temporary files                        |
| `/opt`     | Optional/third-party software          |

📌 **Interview Tip:**
👉 Logs are generally stored in `/var/log`

---

## 3️⃣ Basic Navigation Commands

### 📍 Check current directory

```bash
pwd
```

### 📂 List files and directories

```bash
ls
ls -l      # long listing
ls -a      # show hidden files
ls -la     # long + hidden
```

### 📁 Change directory

```bash
cd foldername
cd ..
cd ~
cd /
```

---

## 4️⃣ File & Directory Management Commands

### 📁 Create directories

```bash
mkdir devops
mkdir linux aws
```

### 📄 Create files

```bash
touch file.txt
touch notes.md
```

### 📄 Copy files

```bash
cp file.txt backup.txt
```

### 📄 Move or rename files

```bash
mv backup.txt newfile.txt
```

### ❌ Delete files & directories

```bash
rm file.txt
rm -r foldername
```

⚠️ **Warning:** `rm -r` permanently deletes files (no recycle bin)

---

## 5️⃣ Viewing & Editing Files

### 👀 View file content

```bash
cat file.txt
```

### ✏️ Edit using nano editor

```bash
nano file.txt
```

**Nano shortcuts:**

* Save → `Ctrl + O` + Enter
* Exit → `Ctrl + X`

---

## 6️⃣ Hands-on Practice (Mandatory)

```bash
cd ~
mkdir linux-practice
cd linux-practice
mkdir day1
cd day1
touch notes.txt
nano notes.txt
```

Add this text:

```
Linux Day 1 practice completed successfully.
```

Save and exit, then verify:

```bash
cat notes.txt
ls -l
```

---

## 7️⃣ Useful Terminal Shortcuts

| Shortcut   | Description           |
| ---------- | --------------------- |
| `Ctrl + C` | Stop running command  |
| `Ctrl + L` | Clear terminal        |
| `Tab`      | Auto-complete command |
| `↑ / ↓`    | Command history       |
| `history`  | Show past commands    |

---

## 8️⃣ Common Mistakes Beginners Make

❌ Using `rm -r /` blindly
❌ Working as root all the time
❌ Not checking directory before deleting
❌ Forgetting `sudo` when required

---

## 9️⃣ DevOps Interview Checkpoint

You should be able to answer:

1. What is Linux and why is it important for DevOps?
2. What does `ls -la` show?
3. Difference between `/bin` and `/usr/bin`?
4. Where are logs stored in Linux?
5. What is the root directory?

---

## 🔚 Day 1 Summary

✔ Learned Linux basics
✔ Understood directory structure
✔ Practiced core commands
✔ Ready for permissions & users

---

