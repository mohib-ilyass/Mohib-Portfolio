Hey! I’m a cybersecurity student diving deeper into Windows security, and this portfolio showcases my hands-on work in Windows Fundamentals Part 3. I explored key security tools like Windows Security, BitLocker, and Volume Shadow Copy Service, learning how to protect systems and data. Below is the rundown of my practical skills, with screenshots to prove my work part of my journey to master cybersecurity and land internships!

## Windows Security

- **What it is**: A central hub in Settings to manage tools protecting your device and data, with status icons (Green = good, Yellow = review, Red = urgent).
- **What I Did**: Opened Windows Security on a Windows 10 and explored its Protection Areas:
    - **Virus & Threat Protection**: Learned about scan options (Quick, Full, Custom) and settings like Real-time Protection, Cloud-delivered Protection, and Controlled Folder Access.
    - **Firewall & Network Protection**: Checked firewall profiles (Domain, Private, Public) and settings like allowing apps or blocking connections.
    - **App & Browser Control**: Noted options for app and browser security settings.
    - **Device Security**: Explored features like BitLocker for encryption.
- **Skills Learned**: Managing antivirus scans, configuring firewalls, and understanding security alerts.
![Windows Security](screenshots/Pasted%20image%2020250920204957.png)

## Virus & Threat Protection

- **What it is**: A Windows Security feature for detecting and managing malware.
- **What I Did**:
    - Explored **Current Threats**: Checked scan options (Quick, Full, Custom) and Threat History (Last Scan, Quarantined/Allowed Threats).
    - Managed **Settings**: Learned about Real-time Protection, Cloud-delivered Protection, Automatic Sample Submission, Controlled Folder Access, Exclusions, and Notifications.
    - Noted: Exclusions and Allowed Threats need caution to avoid vulnerabilities.
    - Tip: Right-click files to scan with Microsoft Defender.
- **Skills Learned**: Running antivirus scans and configuring protection settings safely.
![Virus Threat 1](screenshots/Pasted%20image%2020250920205127.png)
![Virus Threat 2](screenshots/Pasted%20image%2020250920205221.png)

## Firewall & Network Protection

- **What it is**: Controls traffic through ports with three profiles: Domain (for domain-authenticated networks), Private (home networks), Public (Wi-Fi hotspots).
![Firewall](screenshots/Pasted%20image%2020250920205412.png)
- **What I Did**: Navigated to Firewall & Network Protection, checked profile statuses, and explored options to turn the firewall on/off or block incoming connections. Also viewed allowed apps and advanced settings via `WF.msc`.
![Firewall Options](screenshots/Pasted%20image%2020250920205616.png)
- **Skills Learned**: Configuring firewall profiles and managing app permissions for network security.

## App & Browser Control

- **What it is**: Manages Microsoft Defender SmartScreen and Exploit Protection to secure apps and web browsing.
![App Browser Control](screenshots/Pasted%20image%2020250920212313.png)
- **What I Did**:

- **Reputation-based protection (Apps & files)**
    - Checks files and apps you download or run.
    - If they are suspicious or from unknown publishers, SmartScreen warns or blocks them.
![Reputation Protection](screenshots/Pasted%20image%2020250920212246.png)
- **SmartScreen for Microsoft Edge**    
    - Protects you from **malicious websites** (phishing, malware).
    - Blocks harmful downloads in Edge.

- **SmartScreen for Microsoft Store apps**
    - Checks apps you install from the Store.
    - Warns if the app is potentially unsafe.

- **Exploit protection** (in advanced settings)
    - Extra system-level protection against common attack techniques (like buffer overflows).

- **Skills Learned**: Securing apps and browsers against online threats.

## Device Security

- **What it is**: Enhances hardware-based security with features like Core Isolation and Trusted Platform Module (TPM).

- **What I Did**:

    - **Core Isolation**: Learned about Memory Integrity, which prevents malicious code in high-security processes.
    - **Trusted Platform Module (TPM)**: Understood it’s a hardware chip for cryptographic operations, making devices tamper-resistant.
    - Noted: Default settings are best unless you’re an advanced user.

- **Skills Learned**: Leveraging hardware security for system protection.
![Device Security](screenshots/Pasted%20image%2020250920220451.png)

- **What it is**: A drive encryption feature to protect data on lost or stolen devices, works best with a Trusted Platform Module (TPM).
- **What I Did**: Learned how BitLocker encrypts entire drives and requires a PIN, USB key, or recovery key to unlock.
- **Skills Learned**: Understanding disk encryption for data protection.

## BitLocker

- **What it is**: A drive encryption feature to protect data on lost or stolen devices, best with TPM.
- **What I Did**: Learned how BitLocker encrypts drives and uses a PIN, USB key, or recovery key to unlock.
- **Skills Learned**: Using encryption to secure data.

## Volume Shadow Copy Service (VSS)

- **What it is**: Creates snapshots of data for backups, stored in the System Volume Information folder.
- **What I Did**: Explored VSS tasks via Advanced System Settings, like creating restore points, performing system restores, configuring settings, and deleting restore points. Noted malware can target VSS to block recovery.
- **Skills Learned**: Managing system backups and understanding ransomware risks.

## Wrap-Up

Windows Fundamentals Part 3 strengthened my cybersecurity skills with hands-on practice in Windows Security tools. From scanning for malware to configuring firewalls and exploring encryption with BitLocker, I’m building a solid foundation for securing systems.

## Learning Source:

Try Hack Me (Windows Fundamentals Room)
