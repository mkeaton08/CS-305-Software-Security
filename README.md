# CS-305-Software-Security

# Summary
Through the analysis of advanced security concepts, students will learn how to develop secure code that complies with security testing protocols. In addition to exploring and implementing security concepts through code, students will also learn why and how to apply encryption technologies and techniques to communicate securely.

# Briefly summarize your client, Artemis Financial, and its software requirements.
The client Artemis Financial, is a consulting company that provides customized financial plans, including savings, retirement, investments, and insurance. The company was looking to address security vulnerabilities and secure client data. Specifically, Artemis Financial wants to add a file verification step to its web application to ensure secure communications. When the web application is used to transfer data, the company will need a data verification step in the form of a checksum.

# What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
When identifying Artemis Financial’s software security vulnerabilities, I carefully analyzed the codebase to find any vulnerabilities and look for areas that could be improved.Secure coding is crucial because it helps prevent cyber threats such as data breaches, and unauthorized access. Writing secure code ensures that sensitive client information remains confidential and protected. Strong software security builds trust with clients, reduces financial risks, and protects the company’s reputation.

# Which part of the vulnerability assessment was challenging or helpful to you?
The part that was most challenging to me was creating a self-signed certificate that my system could trust. My windows system autpmatically doesn't trust self-signed certificates which caused my webpage to open in an unsecured browser. However, installing the certificate would allow it to be trusted and open the webpage in HTTPS.

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I added multiple security layers by implementing HTTPS, generating self-signed certificates, deploying cryptographic hash functions for verification, and running static code analysis. In the future I will use security tools such as OWASP Dependency check to help identify vulnerabilities and check for any matching CVE's in the National Vulnerability Database.

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
To make sure the code and software were both functional and secure, I tested the updated application after adding encryption, file verification, and HTTPS security. I ran the program to confirm that it worked correctly and that secure communication was enabled. After refactoring, I scanned for any new security vulnerabilities in the updated code to confirm that the changes improved security without breaking the software.

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I used Java Keytool for certificate generation, cryptographic hash functions for data verification, and static analysis tools for vulnerability detection. Secure coding practices such as input validation, encryption, and HTTPS implementation will be valuable in future projects as well as in my professional career as a cybersecurity professional.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
From this assignment, I can show future employers my ability to identify and fix security vulnerabilities in software. I implemented encryption, file verification, and HTTPS security, demonstrating my knowledge of secure coding practices. I also used OWASP Dependency-Check to scan for vulnerabilities, showing my ability to assess and improve software security.
