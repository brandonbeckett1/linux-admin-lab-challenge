## Day 1 – Digital Forensics: File & Permission Sweep
Scenario: You've just taken over a legacy server and need to locate rogue config files, con>
Focus: tree, find, locate, ls -l, umask
### Objectives:
* Find every .conf file under /etc or /opt, sorted by last modified
`find /etc /opt -type f -name "*.conf" -exec ls -lh {} \; | sort -k6,7`

* Use locate to find all .log files, then use du to find the top 3 by size.

* Use tree to map out the structure of /etc/nginx (or another app dir).

* Run umask, explain what it means, then test it by creating files/dirs.

### Deliverables:
* Write a report (~/audit_notes_day1.md) including:

* A list of sensitive .conf files and their permissions

* Your current umask and the effect it had

* Top 3 biggest .log files


