1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?:

My client was Artemis Financial, a company that creates personalized financial plans for clients. They wanted to improve the security of their web application by adding encryption and secure communication features. The main request was to add a checksum verification feature to make sure files weren’t changed during data transfers, along with other secure coding improvements.

4. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?:

I think I did a good job implementing the SHA-256 algorithm for checksums and setting up HTTPS using a self-signed certificate. Secure coding is really important because it helps protect sensitive data from being exposed or tampered with. It also builds trust with users and helps companies avoid serious security issues.

7. Which part of the vulnerability assessment was challenging or helpful to you?:

The most challenging part for me was setting up the certificate and getting HTTPS to work locally. But once I figured it out, it helped me understand how real-world secure communication works.

10. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?:

I added security by using a cryptographic hash, converting the app to HTTPS, and testing for vulnerabilities with a static code analyzer. In the future, I’d use tools like OWASP Dependency-Check again and follow secure coding standards to figure out where vulnerabilities might be.

12. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?:

After changing the code, I tested it by running the app and checking that it worked correctly over HTTPS. I also used Maven's dependency-check tool to make sure I didn’t introduce any new security issues during the changes.

14. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?:

The SHA-256 hashing, Java Keytool for certificate creation, and the Maven dependency-check plugin were all helpful. I’d definitely use those again on similar projects.

16. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?:

I’d show them the full working app with secure HTTPS communication, checksum validation, and a clean dependency-check report. It shows I can write secure code, follow testing protocols, and understand encryption basics.
