# Assignment 4

**Q1: How does the below HTML tag help to protect your privacy online?**

```html
<meta name="referrer" content="origin">
```

**A1:** This tag limits the amount of information sent in the HTTP referrer header when you navigate to another website. Instead of sending the full URL of the page you came from, it sends only the origin, such as the protocol and domain name. This helps protect privacy by reducing the amount of browsing information shared with external sites.

---

**Q2: What information is transmitted in the User-Agent HTTP header?**

**A2:** The User-Agent header typically includes information about the browser, browser version, operating system, rendering engine, and sometimes the device type or model.

---

**Q3: We discussed in lecture the concept of private browsing, also known as "incognito mode." What is an advantage of private browsing?**

**A3:** One advantage of private browsing is that it does not reuse existing cookies and usually does not save local browsing history after the session ends. This can help reduce local tracking and is useful when using a shared or public computer.

---

**Q4: Why might a website use session cookies?**

**A4:** A website may use session cookies to preserve temporary state during a browsing session, such as keeping a user logged in or maintaining the contents of a shopping cart. These cookies are usually deleted when the browser is closed.

---

**Q5: How does Tor prevent someone watching your connection from knowing what websites you visit?**

**A5:** Tor routes traffic through multiple relays and applies layers of encryption, so an observer watching your connection can usually tell that you are using Tor, but cannot easily determine the final website you are visiting. No single relay knows both the sender and the final destination.

---

**Q6: In what sense are domain names similar to phone numbers like 1-800-COLLECT or 1-800-FLOWERS?**

**A6:** Domain names are similar because they provide human-friendly names that correspond to underlying numeric addresses. Just as memorable phone numbers make services easier for people to remember, domain names make websites easier to access without memorizing IP addresses.

---

**Q7: How is Chrome able to put together a user profile for targeted advertising?**

**A7:** Chrome and related Google services can build a user profile by combining browsing activity, search history, cookies, account logins, and other usage signals. Over time, these data points can be correlated to infer user interests and support targeted advertising.

---

**Q8: What is fingerprinting?**

**A8:** Fingerprinting is a tracking technique that identifies or distinguishes a user's device or browser based on a combination of characteristics, such as screen resolution, installed fonts, browser settings, time zone, plugins, and system configuration. Unlike cookies, fingerprinting does not necessarily rely on storing data directly on the device, which makes it harder for users to detect or block.

---

**Q9: Microsoft’s Edge runs in a "sandbox." Why is this good for end-users?**

**A9:** Running the browser in a sandbox is beneficial because it isolates browser processes from the rest of the operating system. If malicious code exploits the browser, the sandbox helps limit what that code can access, reducing the risk of broader system compromise.

---

**Q10: In web server logs, what does the `$http_referer` variable represent, in layman’s terms (without using the word "refer")?**

**A10:** It represents the address of the webpage the visitor came from immediately before arriving at the current page.

---
