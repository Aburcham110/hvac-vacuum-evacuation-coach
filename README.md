# HVAC Vacuum / Evacuation Coach (Educational)

Python **stdlib-only** coach for micron targets, gauge placement, decay/rise interpretation, and pre-charge checklist.

> **Educational only — not a substitute for a calibrated micron gauge or OEM procedure.**

## Quick start

```bash
cd hvac-vacuum-evacuation-coach
python3 vacuum_coach.py --mode coach
python3 vacuum_coach.py --mode interpret-decay --start-micron 350 --after-micron 480 --minutes 10
python3 vacuum_coach.py --mode pre-charge
python3 vacuum_coach.py -i
```
