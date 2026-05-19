# Assignment 3

**Q1: Via what technique(s) might a malicious actor "crack" software (that is, bypass registration/payment to use it)?**

**A1:** A malicious actor might crack software through techniques such as binary patching, key generation, memory hooking, DLL injection, or the creation of fake license validation services. These methods aim to bypass or disable the software's registration and payment checks.

---

**Q2: Distinguish the nature of two types of "cross-site" attacks we discussed: cross-site scripting (XSS) and cross-site request forgeries (CSRF).**

**A2:** **Cross-site scripting (XSS)** involves injecting malicious script into a trusted website so that the victim's browser executes the attacker's code. **Cross-site request forgery (CSRF)**, by contrast, tricks a victim's authenticated browser into sending unintended requests to a trusted website. In short, XSS injects code into the browser, while CSRF abuses the user's existing authenticated session.

---

**Q3: Why do we need to escape certain characters in inputs?**

**A3:** Certain characters must be escaped because they may otherwise be interpreted as control characters or part of a command, query, or markup language. Escaping them ensures they are treated as literal data instead of executable syntax, helping prevent injection attacks.

---

**Q4: In the context of SQL, what is a prepared statement?**

**A4:** A prepared statement is a precompiled SQL query in which the SQL logic is defined separately from the user-supplied data. Instead of directly inserting input into the query string, the application passes the input as parameters. This helps prevent SQL injection and usually improves both security and reliability.

---

**Q5: Why is client-side validation considered "less secure" than server-side validation?**

**A5:** Client-side validation is considered less secure because it runs in the user's own browser, where it can be modified, bypassed, or disabled entirely. Server-side validation is more trustworthy because the checks are performed on the server before the input is processed or stored.

---

**Q6: Even if many users treat open-source software casually, why might it still be a good thing to use (or develop) more open-source software, from a security perspective?**

**A6:** Open-source software can be beneficial from a security perspective because its source code is available for inspection by many developers and security researchers. This transparency can help expose vulnerabilities, accelerate patching, and reduce the chance that hidden malicious behavior will go unnoticed.

---

**Q7: How are package managers similar to app stores (such as Apple’s App Store, Google Play, Microsoft Store, etc.), from a cybersecurity perspective?**

**A7:** From a cybersecurity perspective, package managers and app stores are similar because both act as distribution channels that help users obtain software from trusted sources. They often rely on signatures, verification mechanisms, and policy controls to reduce the risk of tampered, malicious, or untrusted software being installed.

---

**Q8: What threat does use of Content-Security-Policy (CSP) fields in our source code help to defend against?**

**A8:** Content Security Policy (CSP) helps defend primarily against cross-site scripting (XSS) and related injection-based attacks by restricting which sources of scripts, styles, and other content the browser is allowed to load.

---

**Q9: Provide a specific example of a situation when you might want to use the HTTP POST method instead of the HTTP GET method.**

**A9:** A login form is a clear example of when POST should be used instead of GET. Because POST places the submitted data in the request body rather than directly in the URL, it helps avoid exposing usernames, passwords, or other sensitive data in browser history, bookmarks, and server logs.

---

**Q10: Why was Heartbleed such a threat to a user's security?**

**A10:** Heartbleed was such a serious threat because it allowed attackers to read portions of a server's memory without authorization. This leaked memory could contain highly sensitive data such as passwords, private keys, session cookies, and other confidential information. As a result, attackers could compromise both user accounts and the security of the affected service itself.

---