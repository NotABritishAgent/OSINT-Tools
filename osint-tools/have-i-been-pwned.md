---
description: >-
  Tool Description : Check whether an email address, password, or domain has
  appeared in known data breaches.
---

# Have I Been Pwned?

| **Have I Been Pwned?** | **Quick Overview**                                                                                                                                                                                              |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL                    | [https://haveibeenpwned.com/](https://haveibeenpwned.com/)                                                                                                                                                      |
| What it does           | Checks whether email addresses, passwords, or domains have appeared in publicly known data breaches to identify compromised accounts and assess potential cyber risk.                                           |
| How to use it          | Enter an email address or phone number into the search bar to see whether it appears in any known breaches. The site will return a list of breaches and details about the type of data exposed (if applicable). |
| Cost                   | <p>Free (for individual searches).</p><p>Some API access and advanced features require payment.</p>                                                                                                             |
| Account required       | No (for basic searches).                                                                                                                                                                                        |
| Cookies                | Uses standard functional and analytics cookies to operate and improve the site.                                                                                                                                 |
| Ownership              | Developed by Troy Hunt, a well-known Australian cybersecurity expert and Microsoft Regional Director.                                                                                                           |
| Use in Reporting       | Useful for verifying whether email addresses or credentials linked to an investigation have appeared in past breaches, which may indicate account compromise, identity exposure, or additional leads.           |

### **What does Have I Been Pwned do?**&#x20;

Have I Been Pwned (HIBP) is a widely used OSINT and cybersecurity tool that allows users to check whether an email address, password, or domain has appeared in known data breaches. It aggregates breach data from thousands of compromised databases and makes it searchable so users can quickly determine whether credentials or accounts have been exposed.

The service collects and indexes publicly available breach datasets from incidents involving companies, websites, and online services. Users can search for:

* Email addresses
* Phone numbers
* Passwords (via the password search feature)
* Domains (for organisations)

When a match is found, the tool shows which breaches involved the data and what type of information was exposed, such as names, passwords, IP addresses, or payment details.

**The lowdown:** The tool is a breach notification and OSINT lookup service that allows users to check whether personal data has been exposed in data leaks. However, it only shows breaches that are publicly known and does not provide access to the leaked data itself.

### How to Use:

1. **Head to** [**Have I been pwned URL.** ](https://haveibeenpwned.com/)



2. **Enter the email address or phone number you want to check into the search bar.**



3. **Review the results to see if any data breaches have occurred. If it’s your own email address, you’ll likely want to see the below appear:**<br>

<figure><img src="../.gitbook/assets/unknown (39).png" alt=""><figcaption></figcaption></figure>

**If you’re unlucky, you’ll see a result that looks more like this (and you’ll want to make sure you secure/delete that account):**

<figure><img src="../.gitbook/assets/unknown (37).png" alt=""><figcaption></figcaption></figure>

**4. Below the above red box, you’ll find a timeline of data breaches the account appeared in including the types of compromised data (passwords, usernames, IP addresses etc.)**

![](<../.gitbook/assets/unknown (40).png>)<br>

**You can also** [**watch this YouTube Tutorial by Forensic OSINT here.**](https://www.youtube.com/watch?v=JEG29ntQMwo)<br>

### Cost:

* [ ] Paid
* [x] Partially Free
* [ ] Free

Basic searches are free.

API access and some organisational monitoring tools may require payment.

## Data Processing

### Account required:

* [ ] Yes
* [x] No

### Cookies:&#x20;

The site uses basic functional and analytics cookies to maintain site functionality and gather usage statistics.

### &#x20;Use in Reporting

HIBP can support investigations by:

* Confirming whether email addresses connected to individuals or organisations have been compromised.
* Identifying historical breaches that may explain account takeovers.
* Providing context around potential credential exposure.
* Supporting cybersecurity risk assessments.

For example, HIBP was utilised in one of the largest credential leaks in history, known as ‘Collection #1’ containing over 772 million unique email addresses and 21 million passwords. Troy Hunt added it to the database so users including investigators and security teams could quickly identify compromised accounts by searching emails in HIBP.

| **Capabilities**                                             | **Limitations**                                                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------- |
| Searches billions of records of known breaches.              | Only includes breaches that are publicly known/shared with the service.                                 |
| Identifies which breaches affected a specific email address. | Does not provide access to the actual leaked data.                                                      |
| Shows types of data exposed in each breach.                  | Some breach information may be limited/partially redacted.                                              |
| Allows password exposure checks.                             | Results depend on data that has already been discovered/disclosed.                                      |
| Supports domain monitoring for organisations.                | Cannot confirm whether an account is currently compromised, only whether it appeared in past breaches.  |
| Provides API integration for automated security monitoring.  | <p><br></p>                                                                                             |

### Summary

HIBP provides a quick and reliable way to determine whether an email address, password, or domain has been exposed in known leaks, making it valuable for cybersecurity professionals, investigators, journalists, and individuals concerned about digital security.&#x20;

However, results should always be corroborated with other OSINT tools and investigative methods.

### Ownership

Developed by [Troy Hunt](https://www.troyhunt.com/), a well-known Australian cybersecurity expert and Microsoft Regional Director.

### Ethical Considerations:

* Searches should be conducted for legitimate investigative or security purposes.
* Avoid using breach information to access accounts or sensitive systems.
* Results should be handled responsibly as they relate to potentially sensitive personal data.
* Users should comply with data protection regulations and organisational policies.



### Related Tools:

* DeHashed&#x20;
*   IntelX

    <br>

#### Sources:

[https://haveibeenpwned.com/](https://haveibeenpwned.com/)&#x20;

[https://bellingcat.gitbook.io/toolkit/more/all-tools/have-i-been-pwned](https://bellingcat.gitbook.io/toolkit/more/all-tools/have-i-been-pwned)&#x20;

[https://www.recordedfuture.com/threat-intelligence-101/tools-and-technologies/osint-tools](https://www.recordedfuture.com/threat-intelligence-101/tools-and-technologies/osint-tools)&#x20;

[https://medium.com/@samuel.i.steers/have-i-been-pwnd-the-best-beginner-osint-tool-a7ce5d2a4eae](https://medium.com/@samuel.i.steers/have-i-been-pwnd-the-best-beginner-osint-tool-a7ce5d2a4eae)&#x20;

[https://www.troyhunt.com/](https://www.troyhunt.com/)&#x20;

[https://www.youtube.com/watch?v=JEG29ntQMwo](https://www.youtube.com/watch?v=JEG29ntQMwo)&#x20;
