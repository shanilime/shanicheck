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
- Choose light version on modern distros like Arch.
- Choose full version if something wrong with libraries.
---

## Usage

```bash
sudo ./shanicheck-light
```
 or
```
sudo ./shanicheck-full
```

ShaniCheck will automatically locate the Minecraft process and run all checks.

!FALSEFLAG! If you scan one minecraft instance two times, it will cause JVMTI detection because shanicheck attach it's own agent.

---

## Contact

Have a detection you want added? 
Contact the developer directly: **`shanilime`**

---

## License

ShaniCheck is closed-source. Reverse engineering of the binary is not permitted.
