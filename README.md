# Linux_Operations
Day to Day activities of linux Engineer &amp; Configurations


Power On
   │
   ▼
+------------------+
| BIOS / UEFI      |
| - POST           |
| - Detects disks  |
| - Finds bootloader|
+------------------+
   │
   ▼
+------------------+
| Bootloader (GRUB)|
| - Shows menu     |
| - Loads kernel   |
| - Loads initramfs|
+------------------+
   │
   ▼
+------------------+
| Linux Kernel     |
| - Initializes CPU|
| - Mounts root FS |
| - Loads drivers  |
| - Starts init    |
+------------------+
   │
   ▼
+------------------+
| Init / Systemd   |
| - Starts services|
| - udev, network, |
|   logging, SSH   |
| - Sets runlevel  |
+------------------+
   │
   ▼
+------------------+
| Runlevel / Target|
| - Console: multi-user.target |
| - GUI: graphical.target      |
+------------------+
   │
   ▼
+------------------+
| Login Prompt     |
| - TTY login      |
| - GUI login      |
+------------------+
   │
   ▼
User Session / Applications