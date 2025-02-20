# galaxywatch4

**Warning:** This repository is currently not maintained. Use at your own risk!

## Overview

_galaxywatch4_ is a simple Bash script designed to debloat your Galaxy Watch 4—or similar devices—via ADB commands over your local network. It streamlines the process of removing unwanted system packages, giving you more control over your device.

## Prerequisites

- **ADB Installed:** Ensure that ADB (Android Debug Bridge) is installed on your system.
- **Developer Settings Enabled:** On your Galaxy Watch, enable Developer Options and turn on both ADB Debugging and ADB over WiFi.
- **Samsung Health Monitor Mod:** Download the latest version of the Samsung Health Monitor mod from [here](https://drive.google.com/drive/folders/13P3L75wa7_F0CSbZocUvBwCHUN3_M7G_?usp=sharing) and place it in the root directory of the repository.

## Usage Instructions

1. **Customize Your Script:**

   - Open the script and review the list of packages to be removed.
   - Comment out any lines corresponding to packages you wish to keep.

2. **Run the Script:**

   - Open your terminal and navigate to the repository directory.
   - Execute the script:
     ```bash
     ./galaxywatch4.sh
     ```
   - When prompted, enter your Galaxy Watch's IP address followed by `:5555` (e.g., `192.168.1.100:5555`).

3. **Completion:**
   - The script will execute the ADB commands to debloat your device.
   - Once finished, your Galaxy Watch should be running with fewer pre-installed packages.
