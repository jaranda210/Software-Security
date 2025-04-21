# Software-Security

1. Briefly summarize your client, Artemis Financial, and its software requirements.  Who was the client? What issue did the company want you to address?
   
Artemis Financial is a financial services company that needed assistance improving the security of its software.  The company required a vulnerability assessment and secure coding practices to protect sensitive financial data.  They wanted help identifying software security weaknesses and implementing encryption and secure communication protocols to ensure the confidentiality and integrity of data.

2. What did you do well when you found your client’s software security vulnerabilities?  Why is it important to code securely?  What value does software security add to a company’s overall well-being?
   
I was able to effectively identify outdated libraries and potential exposure points in the application.  I implemented secure coding practices, such as using AES-256 encryption and SSL/TLS certificates for secure data transmission.  Coding securely prevents data breaches and protects users’ private information.  Strong software security builds trust, reduces risk, and protects the company’s reputation and compliance standing.

3. Which part of the vulnerability assessment was challenging or helpful to you?

Performing the dependency check and understanding how each vulnerability impacted the application was challenging but very helpful.  It gave me a deeper understanding of how third-party components can introduce risks.

4. How did you increase layers of security?  In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
   
I increased security by implementing AES encryption, enabling HTTPS, using digital certificates, and running a dependency check.  In the future, I would continue using tools like OWASP Dependency-Check, static analysis tools, and threat modeling to identify vulnerabilities and guide mitigation decisions.

5. How did you make certain the code and software application were functional and secure?  After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
   
I tested the application thoroughly after refactoring to ensure it ran correctly without errors.  I used a dependency-check tool to scan for known vulnerabilities and verified that all secure features, such as HTTPS and hash checks, were working as expected.

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
   
I used Spring Boot for application development, OWASP Dependency-Check for vulnerability scanning, and Java’s security libraries for encryption.  These tools and secure coding practices like input validation, secure key handling, and HTTPS setup will be helpful in future projects.

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
   
I would show employers the completed secure communication feature, the use of AES-256 encryption, and the successful implementation of SSL/TLS certificates.  These demonstrate my ability to write secure code, identify vulnerabilities, and apply best practices in cybersecurity.
