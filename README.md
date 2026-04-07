```
 ____  _                 _  ____ _               _    
/ ___|| |__   __ _ _ __ (_)/ ___| |__   ___  ___| | __
\___ \| '_ \ / _` | '_ \| | |   | '_ \ / _ \/ __| |/ /
 ___) | | | | (_| | | | | | |___| | | |  __/ (__|   < 
|____/|_| |_|\__,_|_| |_|_|\____|_| |_|\___|\___|_|\_\
```
> **Linux-native screenshare checking tool for Minecraft**

---

## Overview

ShaniCheck is a screenshare checking utility built for Linux. Designed to help server staff quickly and reliably detect cheats during screenshares.

---

## Requirements

- Linux
- Root privileges (`sudo`)

---

## Usage
```bash
sudo ./shanicheck
```

ShaniCheck will automatically locate the Minecraft process and run all checks.

---

## Known False Positives

**VM detection** — On rare occasions, legitimate hardware using KVM virtualization may be flagged. If a VM is detected, rescan before drawing conclusions.

**GenericInjection** — Always triggers on repeated scans of the same Minecraft process. If the first scan is clean and a subsequent scan flags an inject, this is a false positive — not evidence of injection.

---

## Contact

Have a detection you'd like added?  
Reach out directly: **`shanilime`** on Discord.

---

## License

ShaniCheck is closed-source. Reverse engineering of the binary is not permitted.
