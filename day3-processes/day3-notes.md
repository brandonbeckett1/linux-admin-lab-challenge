## Day 3 – CPU Hog Bounty: Process & Priority Control
**Scenario**: A rogue process is melting the CPU. Identify, throttle, and document it.

### Objectives:
- Simulate CPU load with `yes > /dev/null &`
- Use `top`, `killall`, `nice`, and `renice`
- Log before/after priority impact

### Deliverables:
Create `~/cpu_diag_day3.md`:
- Top output of the CPU hog
- Commands used to control it
- Impact of `nice`/`renice`
