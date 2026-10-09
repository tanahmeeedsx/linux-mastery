# Linux-Mastery — Day 01

## Command: `du`

**Purpose:** Check disk space usage of files and directories.

### What It Does

The `du` command displays how much disk space files and directories use.

### Command Explained

- `du` — Displays disk usage.
- `-s` — Shows the total usage only.
- `-h` — Displays sizes in a human-readable format (KB, MB, GB).

### Practical Examples

Check the total disk usage of the current directory:

```bash
du -sh .
```

Check the total disk usage of the `DAY-01` directory:

```bash
du -sh DAY-01
```

### Example Output

```text
8.0K    DAY-01
```

### Key Takeaway

Use `du -sh` to quickly check the total disk space used by a file or directory.

**Status:** Completed
