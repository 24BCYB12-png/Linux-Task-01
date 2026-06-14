# Linux Task 01 - Command Notes

## Navigation Commands
- `pwd` → Print Working Directory — shows where you are
- `ls` → List files in current folder
- `ls -la` → List ALL files (including hidden ones starting with `.`) with permissions
- `cd` → Change Directory (cd alone = go home)
- `clear` → Clears the screen
- `history` → Shows all commands you've typed before
- `whoami` → Shows your username
- `hostname` → Shows your computer/machine name

## Directory Commands
- `mkdir foldername` → Make a new folder
- `mkdir -p a/{b,c,d}` → Make nested folders all at once
- `tree` → Shows folder structure visually
- `cd foldername` → Go inside a folder
- `cd ..` → Go one folder back

## File Commands
- `touch file.txt` → Create empty file
- `cp source destination` → Copy file
- `mv source destination` → Move OR rename file
- `rm file.txt` → Delete file

## System Info Commands
- `uname -a` → Full kernel/system info
- `hostname` → Machine name
- `whoami` → Current user
- `date` → Current date and time
- `uptime` → How long system has been running
- `pwd` → Current directory path

## Important Tips
- Linux is CASE SENSITIVE → `Reports` ≠ `reports`
- Always check your location with `pwd` before running file commands
- Use `ls` to confirm files/folders exist before copying/moving
- `mkdir Reports` is different from the folder created as `Rports` — typos matter!
