## Day 1 – Digital Forensics: File & Permission Sweep
**Scenario**: You've just taken over a legacy server and need to locate rogue config files, confirm permission hygiene, and prep for a hardening audit.

### Objectives:
- Find every `.conf` file under `/etc` or `/opt`, sorted by last modified
- Use `locate` to find all `.log` files, then use `du` to find the top 3 by size
- Use `tree` to map out the structure of `/etc/nginx` (or another app dir)
- Run `umask`, explain what it means, then test it by creating files/dirs

### Deliverables:
Create `~/audit_notes_day1.md`:
- List of sensitive `.conf` files and their permissions
- Your current umask and the effect it had
- Top 3 biggest `.log` files
