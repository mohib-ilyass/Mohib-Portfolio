Hey! I’m a cybersecurity student leveling up my Windows skills, and this portfolio covers my hands-on work in Windows Fundamentals Part 2. I dug into troubleshooting and system management tools like msconfig, Computer Management, and the Command Prompt, learning how to diagnose issues and configure systems. Check out the key stuff I learned, with placeholders for screenshots to show my practical skills—part of my journey to crush it in cybersecurity and land internships!

## System Configuration (msconfig)

- **What it is**: A troubleshooting tool (msconfig.exe) for fixing Windows startup issues. Requires admin rights.
    
- **What I Did**: Launched it via Start Menu (msconfig) and explored its five tabs:
    
    - **General**: Picked startup modes (Normal, Diagnostic, Selective) to control what loads on boot.
    
        ![](Screenshots/Pasted%20image%2020250915175921.png)


    - **Boot**: Tweaked options like Safe Boot for troubleshooting.
    
        ![](Screenshots/Pasted%20image%2020250915175955.png)

    
    - **Services**: Viewed all services (running or stopped) and practiced disabling them to isolate issues.

        ![](Screenshots/Pasted%20image%2020250915180022.png)

    
    - **Startup**: Noticed it redirects to Task Manager for managing startup items.

	    ![](Screenshots/Pasted%20image%2020250915180100.png)


		**Task Manager interface for startup looks like this:**
		
		![](Screenshots/Pasted%20image%2020250915180211.png)

    - **Tools**: Used commands to launch utilities like Event Viewer.
    
        ![](Screenshots/Pasted%20image%2020250915180302.png)


- **Skills Learned**: Diagnosing startup problems by enabling/disabling services and using Diagnostic/Selective modes.
## Computer Management (compmgmt)

- **What it is**: A central hub for managing system tools, storage, and services.
    
- **Sections I Explored**:
    
    - **Task Scheduler**: Set up automated tasks, like running scripts on a schedule.

		![](Screenshots/Pasted%20image%2020250915184420.png)

	    
	 I myself scheduled a custom task, launched an application at particular time.
	 Let's see how I did so,
	 Go to Create Basic Task a top right of the window.
	 ![](Screenshots/Pasted%20image%2020250915184549.png)

	    ![](Screenshots/Pasted%20image%2020250915184616.png)

		![](Screenshots/Pasted%20image%2020250915184706.png)

		![](Screenshots/Pasted%20image%2020250915184733.png)

		![](Screenshots/Pasted%20image%2020250915184856.png)


    - **Event Viewer**: Checked logs (e.g., Errors, Warnings) to diagnose system issues.
        
        ![](Screenshots/Pasted%20image%2020250915185139.png)
            
    - **Shared Folders**: Saw default shares like C$ and ADMIN$, and checked permissions.
        ![](Screenshots/Pasted%20image%2020250915185211.png)
    - **Local Users and Groups**: Managed accounts using lusrmgr.msc (from Part 1).
        ![](Screenshots/Pasted%20image%2020250915185241.png)
    - **Performance Monitor (perfmon)**: Monitored CPU, memory, and disk usage in real time.
        ![](Screenshots/Pasted%20image%2020250915185335.png)
    - **Device Manager**: Viewed and configured hardware, like disabling devices.
        ![](Screenshots/Pasted%20image%2020250915185348.png)

    - **Disk Management**: Learned to assign drive letters and manage partitions.
        ![](Screenshots/Pasted%20image%2020250915185517.png)

- **Skills Learned**: Managing system resources, analyzing logs, and configuring storage for troubleshooting.
## System Information (msinfo32)

- **What it is**: A tool for viewing detailed hardware, component, and software info.
    
- **What I Did**: Explored sections like:
    
    - **System Summary**: Checked specs like processor model.
        ![](Screenshots/Pasted%20image%2020250915194209.png)

    - **Hardware Resources**: Saw technical details (e.g., IRQs).
        ![](Screenshots/Pasted%20image%2020250915194255.png)

    - **Components**: Found hardware info, like display details.
        ![](Screenshots/Pasted%20image%2020250915194340.png)

    - **Software Environment**: Viewed environment variables and software details.
        ![](Screenshots/Pasted%20image%2020250915194415.png)

    - Searched for IP address in Components to find network info.
        ![](Screenshots/Pasted%20image%2020250915194509.png)

- **Skills Learned**: Gathering system details for auditing and troubleshooting.
## Resource Monitor (resmon)

- **What it is**: Tracks CPU, memory, disk, and network usage per process with real-time graphs.
- **What I Did**: Used tabs (Overview, CPU, Memory, Disk, Network) to monitor system performance and spot resource-heavy processes.
- **Skills Learned**: Diagnosing performance bottlenecks and analyzing process activity.
    ![](Screenshots/Pasted%20image%2020250915194633.png)


## Command Prompt (cmd)

- **What it is**: A text-based interface for running system commands.
- **Commands I Ran**:
    - **hostname**: Got the computer’s name.
	    ![](Screenshots/Pasted%20image%2020250915194958.png)
    - **whoami**: Showed the logged-in user.
	    ![](Screenshots/Pasted%20image%2020250915195023.png)

    - **ipconfig**: Checked network settings like IP address.
	    ![](Screenshots/Pasted%20image%2020250915195104.png)

    - **netstat**: Viewed active network connections (e.g., netstat -a).
	    ![](Screenshots/Pasted%20image%2020250915195304.png)

    - **net**: Explored sub-commands like net user and net share for network resources.
    - Used /? (e.g., ipconfig /?) and net help for command manuals.
    - Also explored more commands.

- **Skills Learned**: Using CLI for system info and network troubleshooting.
## Windows Registry (regedit)

- **What it is**: A database storing configs for users, apps, and hardware.
- **What I Did**: Opened regedit to explore settings like user profiles and hardware details (carefully, since changes can break things!).
- **Skills Learned**: Understanding how Windows uses the registry for system configuration.
    ![](Screenshots/Pasted%20image%2020250915205313.png)


## Wrap-Up

Windows Fundamentals Part 2 boosted my cybersecurity skills with hands-on practice in troubleshooting and system management. From tweaking startups with msconfig to analyzing logs in Event Viewer and running ipconfig, I’m ready for sysadmin and pentesting challenges. Check my GitHub for more projects.

## Learning Source:

Try Hack Me (Windows Fundamentals Room)