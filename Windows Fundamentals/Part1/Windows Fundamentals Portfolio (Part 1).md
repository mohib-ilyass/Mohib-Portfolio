Hey, I’m sharing what I learned in Windows Fundamentals 1 to show off my cybersecurity skills. I did the hands-on stuff, and here’s the rundown with some screenshots to prove it!
## File Systems

- **NTFS**: Windows’ main file system. It logs changes to fix crashes, supports big files, permissions, and encryption (EFS).
- **FAT**: Used for USBs, not as secure or fancy.
- **Alternate Data Streams (ADS)**: NTFS can hide data, which hackers might use. Tools like `streams.exe` can find it.
Windows uses NTFS as shown in screenshot below:

![](screenshots/Pasted%20image%2020250914153611.png)
## Windows Folder

- **What’s up**: The `C:\Windows` folder (or `%windir%`) holds system files like `System32`. It’s where the OS lives.
## Users and Profiles

- **Account Types**: Admins can do anything; Standard Users are limited to their own files.
- **Managing Users**: I used `lusrmgr.msc` to check accounts. Here’s what it looked like:  
- **Profiles**: Each user gets a folder like `C:\Users\Max`.

For this purpose go to run and type **lusrmgr.msc**
![](screenshots/Pasted%20image%2020250914151757.png)
Click OK

You will get this window
![](screenshots/Pasted%20image%2020250914151927.png)
I played with all the stuff here like viewing information about the users. I also created and deleted a user, added it into the group, and deleted it.
## User Account Control (UAC)

- **What it does**: Asks for permission before big changes, even for Admins. Standard Users need an Admin password.
- **Example**: I tried installing Wireshark as a Standard User and got this UAC prompt:  

**UAC setting interface**
![](screenshots/Pasted%20image%2020250914152536.png)
I played with the settings here and got to know the importance of UAC.
## Settings and Control Panel

- **Settings**: Easy spot for basic changes like wallpaper.
- **Control Panel**: For deeper stuff like network settings.
- **Tip**: Search the Start Menu to find what you need.

**Control Panel:**
![](screenshots/Pasted%20image%2020250914152822.png)
I also played with the features of control panel.

**Settings**
![](screenshots/Pasted%20image%2020250914153024.png)
I also explored some settings features like shown in above screenshot.
## Task Manager

- **What it does**: Shows running apps and CPU/RAM usage.
- **How I used it**: Checked processes to see what’s up with my system.

**Task Manager Interface**
![](screenshots/Pasted%20image%2020250914153410.png)
## Wrap-Up

I got hands-on with Windows, from permissions to UAC, and these screenshots show I practically done these tasks.

## Learning Source:

Try Hack Me (Windows Fundamentals Room)