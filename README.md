# SHNU-CS305
SNHU CS305

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial required improved security for their software by implementing encryption and checksum verification. Their requirements specified a way to verify the integrity of a public key distribution. This required an industry standard encryption algorithm that avoided collision and implemented the checksum function.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
Ensuring industry standard security practices were followed, as well as reviewing the vulnerability assessments and suppressing false positives. Secure coding practices prevent common security issues such as data breaches, unauthorized access, and system failures. Strong security reduces the risk of costly breaches and compliance violations, ensuring business continuity and maintained public trust.

Which part of the vulnerability assessment was challenging or helpful to you?
Understanding the assessment was a challenge. Trying to understand how or if certain threats applied to the project was very time consuming. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased the security through layers by implementing a check sum verification with SHA-256 hashing algorithm. I would continue to use the OWASP dependency check to review dependencies, suppress false-positives, and review CVEs to ensure proper mitigations are put in place. 

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
After refactoring the code, I ran the main file and ensured I could establish an HTTPS conenction to the page and verified my certificate. Once I ensured the code base was correct, I ran a final dependency check to ensure no new vulnerabilites were introduced. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
OWASP for dependency checks and JavaDocs for coding practices.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
A successful implemention of a check sum verification and SHA-256 hashing algorithm, in addition to certificate generation and trust. 
