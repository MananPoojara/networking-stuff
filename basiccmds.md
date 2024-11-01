# Learning Basic Linux Commands

## Listing Files and Directories

Use the `ls` command to list files and directories in the current folder:

```bash
~ …
➜ ls
 Backup                          pracfolder
 descriptor.xml                  Public
 Desktop                         snap
 Documents                       Sync
 Downloads                       Templates
 dwrcx-hawyh                     Videos
 file1.txt                       vmware
 file2.txt                       vmware-host-modules-workstation-17.5.1
 mergerd.txt                     VMware-Workstation-17.5.2-23775571.x86_64.bundle
 Music                           VMware-Workstation-17.5.2-23775571.x86_64.bundle.tar
 Pictures                        workstation-17.5.1.tar.gz
"PlayOnLinux's virtual drives"
```

## Echo Command

To print a message to the terminal, use the `echo` command:

```bash
~ …
➜ echo "let's learn some basic commands"  
let's learn some basic commands
```

You can also print information about similar commands that show more details about files and folders:

```bash
~ …
➜ echo "ls -la, ll, ls -l work the same but give more info"
ls -la, ll, ls -l work the same but give more info to you
```

## Displaying Detailed File Information

### `ls -l`
The `ls -l` command provides a long listing format, showing detailed file information like permissions, owners, file size, and modification date:

```bash
~ …
➜ ls -l
total 394372
drwx------ 57 manan manan      4096 Oct 28 20:31  Backup
-rw-rw-r--  1 manan manan      1142 Apr 30  2024  descriptor.xml
drwxr-xr-x  8 manan manan      4096 Oct 28 18:51  Desktop
drwxr-xr-x  3 manan manan      4096 Oct 29 14:59  Documents
drwxr-xr-x  6 manan manan      4096 Nov  1 12:59  Downloads
drwxrwxr-x  2 manan manan      4096 Oct 28 19:04  dwrcx-hawyh
-rw-rw-r--  1 manan manan        23 Oct 26 13:57  file1.txt
-rw-rw-r--  1 manan manan        25 Oct 26 13:57  file2.txt
-rw-rw-r--  1 manan manan         0 Oct 26 14:03  mergerd.txt
drwxr-xr-x  2 manan manan      4096 Oct 20 00:50  Music
drwxr-xr-x  4 manan manan      4096 Oct 25 09:45  Pictures
lrwxrwxrwx  1 manan manan        37 Oct 20 21:02 "PlayOnLinux's virtual drives" -> /home/manan/.PlayOnLinux//wineprefix/
drwxrwxr-x  3 manan manan      4096 Nov  1 20:52  pracfolder
drwxr-xr-x  2 manan manan      4096 Oct 20 00:50  Public
```

### `ls -la`
Use `ls -la` to view hidden files (those starting with a dot) along with file details:

```bash
~ …
➜ ls -la
total 394904
drwxr-x--- 40 manan manan      4096 Nov  1 20:53  .
drwxr-xr-x  3 root  root       4096 Oct 20 00:44  ..
drwx------ 57 manan manan      4096 Oct 28 20:31  Backup
-rw-------  1 manan manan      2843 Oct 26 14:00  .bash_history
-rw-r--r--  1 manan manan       220 Oct 20 00:44  .bash_logout
-rw-r--r--  1 manan manan      3780 Oct 30 10:47  .bashrc
drwx------ 30 manan manan      4096 Nov  1 15:01  .cache
drwx------ 29 manan manan      4096 Oct 30 11:02  .config
-rw-rw-r--  1 manan manan      1142 Apr 30  2024  descriptor.xml
drwxr-xr-x  8 manan manan      4096 Oct 28 18:51  Desktop
drwxr-xr-x  3 manan manan      4096 Oct 29 14:59  Documents
drwxrwxr-x  4 manan manan      4096 Oct 21 18:11  .dotnet
drwxr-xr-x  6 manan manan      4096 Nov  1 12:59  Downloads
```

## Key Takeaways

- **`ls`**: Lists files and directories in the current directory.
- **`echo "text"`**: Prints text to the terminal.
- **`ls -l`**: Lists files with details (permissions, owners, size, etc.).
- **`ls -la`**: Lists all files (including hidden files) with details.
- **Similar Commands**:
  - `ls -la`, `ll`, `ls -l` provide more details about files than `ls` alone.

This `.md` file summarizes basic Linux commands for listing and displaying file details with explanations and examples.
