# Assignment 0

**Q1: Why might being required to change our passwords regularly actually pose a threat to our security?**

**A1:** Requiring frequent password changes can unintentionally weaken security because users may respond by choosing simpler, more predictable passwords or making only minor variations to old ones. These habits make passwords easier for attackers to guess while also making them harder for users to remember.

---

**Q2: If I have a six-character password consisting of uppercase (English) letters and (decimal) digits only, how many seconds might it take an adversary to crack, assuming they make one attempt per second?**

**A2:** A six-character password using 26 uppercase letters and 10 digits has 36 possible characters per position, so the total number of combinations is 36^6 = 2,176,782,336. At one guess per second, it could therefore take up to 2,176,782,336 seconds to crack.

---

**Q3: Humor us for a moment, and play The Password Game, trying to get through at least Rule 12. While obviously the game itself is in many ways meant to be humorous, it also critiques the experience many of us have setting up new passwords. Explain how there's a trade-off between usability and security in the context of passwords.**

**A3:** The Password Game humorously illustrates how excessive password rules can make the user experience frustrating without necessarily improving security. When password requirements become too complicated, users are more likely to create passwords that are hard to remember, reuse patterns, or write them down. This shows the trade-off between usability and security: stronger rules may increase theoretical security, but if they overwhelm users, they can lead to weaker real-world behavior.

---

**Q4: Consider the top row of the xkcd comic (936). Why are passwords like those easy (for a computer) to guess but hard (for a human) to remember?**

**A4:** Passwords like those in the top row often rely on predictable substitutions, such as replacing letters with numbers or symbols. Although they may look complex to humans, computers can guess them efficiently using dictionary-based and brute-force strategies. At the same time, they are difficult for humans to remember because they do not form a meaningful or memorable pattern.

---

**Q5: Now consider the bottom row of the comic above. Why are passwords like those hard (for a computer) to guess but easy (for a human) to remember?**

**A5:** Passwords in the bottom row are made of multiple random but common words, which creates a much larger search space and therefore higher entropy. This makes them more difficult for computers to guess. For humans, however, the words form a phrase that is easier to visualize, understand, and remember.

---

**Q6: What is a "credential stuffing" attack?**

**A6:** A credential stuffing attack is a type of attack in which stolen usernames and passwords from one data breach are automatically tested on other websites and services. It is effective because many users reuse the same credentials across multiple accounts.

---

**Q7: Provide a specific example of something that would be considered a type of knowledge factor for authentication purposes.**

**A7:** A Personal Identification Number (PIN) is an example of a knowledge factor because it is something the user knows.

---

**Q8: Provide a specific example of something that would be considered a type of inherence factor for authentication purposes.**

**A8:** A fingerprint scan is an example of an inherence factor because it is based on something the user is.

---

**Q9: Why are phishing attacks so difficult to prevent?**

**A9:** Phishing attacks are difficult to prevent because they target human judgment rather than only technical weaknesses. Attackers often create emails, messages, or websites that look convincing and exploit urgency, trust, or fear to trick users into acting quickly. Even well-trained users can make mistakes, especially when phishing attempts closely imitate legitimate organizations.

---

**Q10: Suppose that your boss asks you whether the company should require use of password managers for all employees. Explain in a short paragraph why you might want everyone in the company to use a password manager.**

**A10:** Requiring employees to use a password manager can significantly improve organizational security. Password managers make it easier to generate and store strong, unique passwords for every account, reducing the risk of weak passwords and password reuse. This helps protect the company from attacks such as credential stuffing while also making login management more convenient for employees. In this way, password managers improve both security and usability at the same time.

---