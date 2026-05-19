# Assignment 2

**Q1: Considering its nature, what type of cybersecurity threat might pose the most unique risk to research projects like SETI@Home? How might such a threat be realized?**

**A1:** A supply chain compromise poses a particularly unique risk to research projects like SETI@Home because the project depends on distributed trust between a central server and many volunteer systems. If attackers were to compromise the project's infrastructure, they could distribute malicious updates or work units to participants. As a result, volunteers might unknowingly execute harmful code, allowing attackers to spread malware or build a botnet.

---

**Q2: What is a zero-day attack, and why are such attacks a threat?**

**A2:** A zero-day attack exploits a software vulnerability that is unknown to the vendor or has not yet been patched. These attacks are especially dangerous because defenders have little or no time to prepare protections before the exploit is used in the wild.

---

**Q3: What is port scanning and how does it pose a threat?**

**A3:** Port scanning is the process of probing a device's network ports to identify which services are open and available. It becomes a threat because attackers can use the results to map a target system, identify exposed services, and look for weaknesses they can exploit.

---

**Q4: What is a supercookie? How do we typically acquire/receive them, and how might they threaten our systems?**

**A4:** A supercookie is a highly persistent tracking mechanism that can remain on a system or reappear even after ordinary cookies are deleted. It may be delivered through browser storage mechanisms, network-level injection, or other tracking methods used by websites or service providers. Supercookies threaten privacy by enabling persistent tracking and may also contribute to more targeted attacks or session-related abuse.

---

**Q5: How do worms differ from viruses?**

**A5:** A worm is a self-replicating type of malware that can spread automatically across networks without requiring user action. A virus, by contrast, usually attaches itself to another file or program and spreads when the infected host is executed. In short, worms spread independently, while viruses usually depend on user activity.

---

**Q6: Provide an example of a technique that implements “security through obscurity.”**

**A6:** One example is running an SSH service on a non-standard port instead of the default port 22. This does not make the service truly secure on its own, but it may reduce casual scanning and unwanted attention.

---

**Q7: Distinguish between SSH and VPN.**

**A7:** SSH and VPN both provide secure communication, but they serve different purposes. A **VPN** creates an encrypted tunnel that can protect all or most network traffic between two points. **SSH**, on the other hand, is mainly used to securely log in to a remote machine, execute commands, or transfer files over an encrypted connection.

---

**Q8: What is the purpose of the X.509 standard?**

**A8:** The X.509 standard defines the format and structure of public key certificates used in Public Key Infrastructure (PKI). It helps bind identities to public keys and is widely used in systems such as SSL/TLS, secure email, and code signing.

---

**Q9: Why might companies conduct penetration tests?**

**A9:** Companies conduct penetration tests to identify security weaknesses before attackers do. These tests help validate existing defenses, reveal misconfigurations or vulnerabilities, support compliance requirements, and reduce the likelihood and impact of real-world breaches.

---

**Q10: Which HTTP status code is most likely to indicate that a Distributed Denial of Service (DDoS) attack is underway?**

**A10:** **503 Service Unavailable** is the status code most likely to indicate this situation, because it suggests that the server is temporarily unable to handle requests, which can happen when it is overwhelmed by excessive traffic.

---