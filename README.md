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
- Root privileges

---
## Which version to choose?
- Choose normal version on modern distros like Arch.
- Choose snandalone version if something wrong with libraries.
---

## Usage

```bash
sudo ./shanicheck
```
 or
```
sudo ./shanicheck-standalone
```

ShaniCheck will automatically locate the Minecraft process and run all checks.

---
## FalseFlags:
1. VM detection once detected my normal pc as VM: KVM, the chance is very low but be carefull. You should rescan pc if VM is detected.
2. JNI/JVMTI inject: It will alsways be falseflag if you scan minecraft multiple times. So if first scan doesn't show inject and second scan show it, it doesn't mean person injected something.
---

## Contact

Have a detection you want added? 
Contact the developer directly: **`shanilime`**

---

## License

ShaniCheck is closed-source. Reverse engineering of the binary is not permitted.
