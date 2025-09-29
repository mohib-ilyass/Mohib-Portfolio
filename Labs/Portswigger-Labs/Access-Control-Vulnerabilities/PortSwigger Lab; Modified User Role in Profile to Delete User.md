![[../../Pasted image 20250922175916.png]]
Hey! I’m a cybersecurity student diving into web hacks, and this portfolio covers how I solved a PortSwigger lab by modifying the user role in the profile to access the admin panel and delete "carlos." I used Burp Suite to intercept and tweak requests, hands-on fun! Here’s the breakdown, with screenshots to prove my work, part of my journey to level up in pentesting.

## Lab Overview

- **Goal**: Log in as a standard user, modify the role ID to gain admin access, and delete the user "carlos."
- **Vulnerability**: User role can be changed via a modifiable parameter in the request.

## What I Did

1. **Logged In**: Signed in as a standard user (wiener) with default credentials and fired up Burp Suite to capture traffic.
    
![](screenshots/Pasted%20image%2020250922190007.png)
        
2. **Updated Email & Captured Request**: Tried updating my email by filling in a new one and hitting enter. Captured the request in Burp Suite, noticing "roleid = 1" in the response.
![](screenshots/Pasted%20image%2020250922190136.png)
Got this request and response on burp:

![](screenshots/Pasted%20image%2020250922191052.png)

3. **Modified Role ID**: Sent the request to Burp Repeater, added "roleid = 2" in JSON format alongside the email update, and sent it to the server. The role ID switched to 2!
    
    - ![](screenshots/Pasted%20image%2020250922191355.png)
        
4. **Accessed Admin Panel & Deleted Carlos**: Navigated to "/admin" in the URL, hit enter, and boom—logged in as admin. Deleted "carlos" to complete the lab.
    
![](screenshots/Pasted%20image%2020250922191533.png)

Accessed the admin portal and deleted the user:

![](screenshots/Pasted%20image%2020250922191639.png)

Lab solved:
![](screenshots/Pasted%20image%2020250922191804.png)

## Skills Learned

- Intercepting and modifying HTTP requests with Burp Suite.
- Exploiting insecure direct object references (IDOR) by changing role IDs.
- Escalating privileges through manipulated parameters.
- Practical web pentesting to identify and exploit role-based vulnerabilities.

## Thoughts

This lab was wild! Tweaking that "roleid" from 1 to 2 felt like unlocking a secret level—shows how sloppy input validation can open doors. Burp Repeater is clutch for testing these changes. Ready to tackle more!

## Wrap-Up

Nailed this PortSwigger lab by modifying the role ID to access the admin panel and delete "carlos." Stoked to keep sharpening my skills! Check my GitHub for other projects.

## Learning Source

PortSwigger Academy (Access Control Labs)
