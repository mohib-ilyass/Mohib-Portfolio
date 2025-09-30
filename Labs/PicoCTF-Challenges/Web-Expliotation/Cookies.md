**What the challenge was?**
![](../../../screenshots/Pasted%20image%2020250930172146.png)

**How did I solve it?**

clicked the given link and went to this page 
![](../../../screenshots/Pasted%20image%2020250930172622.png)
Here when I put random values, I got this:
![](../../../screenshots/Pasted%20image%2020250930172731.png)
Then I put a valid cookie 'wafer' and got this:
![](../../../screenshots/Pasted%20image%2020250930172823.png)
I inspected the page for both of the behavior (for valid and invalid cookie) and notice that,
For valid cookie the cookie 'name' is a valid number greater than -1,
![](screenshots/Pasted%20image%2020250930173155.png)
but for invalid cookie it was always 1.

What is did then,
- I opened burpsuite
- Sent the request to intruder
- Loaded the payload
- Started the attack

What I found:
![](../../../screenshots/Pasted%20image%2020250930173635.png)

I got the flag and hence i completed the challenge.

#### Skills learned

- **HTTP request inspection** — Observed request/response flow and cookie values using browser DevTools.
- **Cookie analysis & tampering** — Understood how the app used the `name` cookie (valid vs invalid numeric values) and changed cookie values to alter behavior.
- **Behavioral difference analysis** — Compared valid vs invalid responses to infer server-side logic (numeric check > -1).
- **Burp Suite (Intruder) usage** — Sent requests to Intruder, loaded payloads, and automated testing to enumerate valid cookie values.
- **Fuzzing / enumeration** — Systematically tried payloads to discover which values triggered the flag.
- **Automation mindset** — Replaced manual guessing with an automated attack to save time and reliably find the flag.
- **Response validation** — Parsed server responses to detect success conditions (how the page changed when cookie was valid).
- **Practical troubleshooting** — Combined browser inspection and proxy tools to verify hypotheses and iterate quickly.
- **Documentation & reporting** — Captured screenshots and wrote clear step-by-step notes suitable for a writeup or lab report.

#### Learning Source:
PicoCTF Challenges
