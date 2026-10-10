# Linux-Mastery — Day 01

**Focus:** Practical Linux Commands  
**Duration:** 1 Hour  
**Commands:** 5

---

### 1. `stat`
View detailed file information.

```bash
stat /etc/hostname
stat -c '%A %U %G %n' /etc/hostname
```

### 2. `find`
Search for files and directories.

```bash
find DAY-01
find /etc -type f -name "hostname" 2>/dev/null
```

### 3. `xargs`
Pass command output to another command.

```bash
find DAY-01 -type f | xargs ls -l
find DAY-01 -type f | xargs -n 1 basename
```

### 4. `tee`
Display and save output simultaneously.

```bash
echo "Linux-Mastery Day 01" | tee DAY-01/notes.txt
echo "Another Linux lesson" | tee -a DAY-01/notes.txt
```

### 5. `du`
Check disk space usage.

```bash
du -sh .
du -sh DAY-01
```

---

## Progress

**Day 01 — Completed**

**5 Commands · 1 Hour · Hands-on Practice**
