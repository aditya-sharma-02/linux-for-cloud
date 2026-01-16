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

## The `/tmp` folder
- It stores short lived files that is created by 
    - running programs
    - users

## The `/usr/bin` folder
- It contains command binaries.
- In simple terms ***normal user applications*** & ***commands***.
- It stores thousands of commands we use daily such as:
    - **vim**
    - **nano**
    - **git**
    - **python**, **java**
    - **gcc** 
and others.

## The `/usr/share` folder
- It contain architecture-independent read-only data used by programs.
- In short it stores data not executables.
- Such as:
    - documentations
    - icons
    - themes
    - man pages
    - fonts

## The `/home` folder
- It stores personal directories for regular users.
- If a new user is created it stores in this directory: `/home/username`.
- And all the files lives here i.e. inside `/home/username`
    - ***Documents***
    - ***Downloads***
    - ***Videos***
    - ***Music***

## The `/root` folder
- It is a directory not a root filesystem.
- It contains **admin's personal workspace**.
- Only **root** can access it.
    - `/home/username` - normal user
    - `/root` - root user.