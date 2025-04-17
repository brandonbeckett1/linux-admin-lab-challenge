## Day 2 – Sysadmin Onboarding: Live Log & Edit Drill
**Scenario**: You're SSH’d into a production server. Logs are flying. You need to troubleshoot *and* tweak configs without breaking anything.

### Objectives:
- Use `tail -f` on `/var/log/syslog` or `/var/log/auth.log`
- In another terminal, trigger an event (restart a service)
- Use `grep` + `less` to find failed login attempts
- Edit `/etc/ssh/sshd_config` with `vim`, save, reload SSH

### Deliverables:
Create `~/vim_checkpoint_day2.md`:
- Summary of logs watched
- Vim commands used
- Any SSH-related logs or changes seen
