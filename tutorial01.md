# File System in Linux
- A file system is a method for storing and organising files. 
- It is a set of processes that controls where and when data is stored or retrieved from storage device.
- **Linux treats everything as a file including devices and applications.**
- Everything in linux starts from a single point, i.e. roor directory which is denoted by a **forward slash**.
- For instance: `/` means root directory.

## The `/bin` folder
- It stands for **binary**.
- It stores basic programs such as `ls`, `cd`, `mv` etc.
- They are the essemtial user commands needed for the system to work at a minimum level.

## The `/sbin` folder
- It stands for system binaries.
- Stores system program such as `fdisk`, `sysctl`, `mkfs` etc.
- This folder is neede to boot, repair, configure and manage the system.
- It also helps to interact with hardware.
- Example: 
    - `fsck` - filesystem check
    - `moun` & `unmount` - mount filesystem, and
    - `reboot`, `shutdown`, etc.

## The `/etc` folder
- It stores system-wide configuration files or we can say ***settings of linux***.
- It only stores **text-based configuration** files that controls how the system & services behave.
- Example:
    - `/etc/password` - user accounts
    - `/etc/groups` - groups
    - `/etc/hosts` - local DNS mapping.
- System won't boot properly if `/etc` is broken.