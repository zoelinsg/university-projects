# Assignment 1

**Q1: Characterize the difference between a database hack and a database leak.**

**A1:** A database hack usually involves unauthorized access gained through an active attack, such as exploiting a vulnerability, bypassing authentication, or stealing credentials. A database leak, by contrast, often happens when data is exposed unintentionally, such as through a misconfigured server, poor access controls, or accidental publication. In short, a hack is typically the result of intrusion, while a leak is often the result of improper exposure.

---

**Q2: In what sense might files not actually be deleted even if you empty the recycle bin on Windows or empty the trash on macOS?**

**A2:** Emptying the Recycle Bin or Trash usually removes the system's references to the file rather than immediately erasing the file's actual data from the storage device. Until that space is overwritten by new data, the original contents may still be recoverable with forensic or recovery tools.

---

**Q3: How do quantum computers differ from traditional (non-quantum) computers?**

**A3:** Traditional computers process information using bits that are either 0 or 1. Quantum computers use qubits, which can exist in superposition and can also be entangled with one another. These properties allow quantum computers to solve certain types of problems much more efficiently than classical computers, including some problems related to cryptography.

---

**Q4: What is the term for the prevailing method via which public-key (i.e., asymmetric) cryptography enables two parties to establish a shared secret, even over an insecure (i.e., unencrypted) channel?**

**A4:** The prevailing method is called the **Diffie–Hellman key exchange**.

---

**Q5: What is a salt, in the context of this lecture?**

**A5:** A salt is a random value added to a password before it is hashed. Its purpose is to ensure that even if two users choose the same password, their resulting hashes will be different, making precomputed attacks such as rainbow table attacks much less effective.

---

**Q6: Suppose that Alice and Bob need to coordinate a meeting, as by exchanging emails using Microsoft Outlook, a popular client for email. If their emails are encrypted in-transit, who (besides Alice and Bob, or anyone with access to their computer) might nonetheless be able to read the emails, if anyone?**

**A6:** If the emails are only encrypted in transit, the email provider and anyone with access to the email servers may still be able to read them once they arrive or while they are stored. In-transit encryption protects the message while it travels across the network, but it does not necessarily provide end-to-end confidentiality.

---

**Q7: Suppose that you have been hired to perform some work for Charlie. After agreeing to terms, you send the contract to Charlie via email, and, later that day, you receive a digitally signed copy from an email address that appears to belong to Charlie but isn't the one to which you sent the contract originally. How can you be as certain as possible, technologically (that is, without consulting Charlie) that Charlie was the one who digitally signed the contract?**

**A7:** To be as certain as possible technologically, you would verify the digital signature using Charlie's public key. If the signature validates correctly with a trusted copy of Charlie's public key, that provides strong evidence that the contract was signed using the corresponding private key and that the document was not altered after signing.

---

**Q8: Suppose that a company has made a large file available for download via its website. Why might they also make available the MD5 hash of that file (as is indeed a common practice)?**

**A8:** The company may publish the MD5 hash so users can verify the integrity of the downloaded file. After downloading it, a user can compute the file's MD5 hash and compare it to the published value. If the values match, it suggests that the file was not corrupted or modified during transfer.

---

**Q9: Identify one or more significant differences between a cipher and a hash.**

**A9:** A cipher and a hash serve different purposes. A **cipher** is designed for reversible transformation: it uses a key to encrypt plaintext into ciphertext and can later decrypt it back into the original data. A **hash**, on the other hand, is designed to be one-way: it turns input data into a fixed-size digest that cannot practically be reversed. Ciphers are mainly used for confidentiality, while hashes are mainly used for integrity verification and secure storage of password-related data.

---

**Q10: Otkz D zvmizy v amzz kjdio! di ocz wjs wzgjr. (Not random typing.)**

**A10:** “Type I earned a free point!”

---