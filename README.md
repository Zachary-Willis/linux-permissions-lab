#  Linux Permissions Lab

A practice project using Linux commands to explore and manage file permissions. This lab demonstrates how to properly secure sensitive files, identify misconfigurations, and apply the principle of least privilege.

---

## 📅 Date

2025-06-04

---

## 🧠 Skills Demonstrated

- Navigating Linux file systems via command line
- Viewing and modifying file permissions using `chmod`, `chown`, and `ls -l`
- Setting special permission bits (SUID, SGID, sticky bit)
- Enforcing least privilege principles

---

## ⚙️ Tools & Technologies

- Linux Terminal / Bash
- Ubuntu VM (or WSL, or cloud-based Linux shell)
- `chmod`, `chown`, `ls`, `touch`, `mkdir`, `nano`

---

## 🧪 Lab Scenario

🔍 You’re given a Linux server with multiple misconfigured files and folders.  
🛠️ Your job is to audit and correct permissions.  
You:
- Run `ls -l` to find overly permissive files.
- Use `chmod 600` to lock down private keys.
- Set `chmod 755` on public scripts.
- Fix a world-writable directory with a sticky bit: `chmod +t`.

✅ All files secured. Audit log saved.

---

## 📁 Files

- `audit-log.md`: Summary of changes made
- `commands-used.txt`: Exact terminal commands
- `screenshots/`: Before & after permission changes

---

## 📝 Notes

This lab proves you're confident working in Linux environments — essential for real-world security jobs. Pair it with incident response or SQL labs for a well-rounded portfolio.

---

## 🔗 References

- [Linux Permissions Explained](https://linuxize.com/post/understanding-linux-file-permissions/)
- [chmod Manual](https://man7.org/linux/man-pages/man1/chmod.1.html)
