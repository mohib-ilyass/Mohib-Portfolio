This document describes my approach to solving the challenge “Local Authority” on PicoCTF.
I explain the problem, the tools and commands I used, the vulnerabilities I discovered, and the final flag. The purpose is learning and documentation — all testing was performed only on the given CTF target. 
**Tools used:**  Browser DevTool

Given challenge is:
![](screenshots/Pasted%20image%2020250930193558.png)
I have given this web page
![](screenshots/Pasted%20image%2020250930195601.png)

I tried login in with random passwords but login failed always
![](screenshots/Pasted%20image%2020250930195753.png)

I inspected the page after failed login found an insecure javascript file where password was visible:
![](screenshots/Pasted%20image%2020250930195924.png)
I used the credentials to login and got the flag.

**Vulnerabilities & Fixes:**

1. **Client-side auth / hardcoded password** → Move auth to server, hash passwords.
2. **Weak authorization** → Use server-checked sessions, secure cookies.
3. **Single factor** → Add 2FA or passkeys for sensitive accounts.

**Skills Learned:**
- Inspecting and analyzing **JavaScript** in webpages.
- Understanding **client-side vs server-side authentication**.
- Identifying **security vulnerabilities** (hardcoded credentials, weak auth).
- Using **DevTools / console** to test login logic.
- Documenting and explaining **CTF exploitation steps**.
