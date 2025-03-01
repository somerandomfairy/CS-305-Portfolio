# CS-305-Portfolio
# Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a consulting company that creates personalized financial plans. It is seeking to modernize its operations, specifically to enhance the security of its public web interface and RESTful API and protect client data by adding secure communication mechanisms such as checksums for file verification and HTTPS encryption. 

# What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

Some aspects where I’ve done well includes identifying and documenting security vulnerabilities in the client’s software using OWASP Dependency-Check. I also refactored  the code to implement SHA-256 for checksum verification. Further, I successfully configured the application to use HTTPS for secure communication. 
Secure coding is important because it plays a critical role in protecting sensitive data, maintaining stakeholder trust, and ensuring industry and regulatory compliance. Software security adds tremendous value to a company’s overall well-being by prevening data breaches, financial losses, and reputation damage. 

# Which part of the vulnerability assessment was challenging or helpful to you?
One aspect of the vulnerability assessment I found challenging was refactoring the code to use HTTPS, as I struggled with setting up the keystore and making sure that the IDE was able to locate it. This required a lot of troubleshooting, but eventually, I was successful in the endeavor. 

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
To increase layers of security, I did the following: Implement checksum verification using SHA-256 to ensure data integrity; Configure the application to use HTTPS for secure communication, and; Conduct static code analysis using OWASP Dependency-Check to identify vulnerabilities. In the future, I would continue to apply the techniques I learned in this course by performing static analysis and functional testing to identify vulnerabilities and adhering to industry best practices to ensure security. 

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
To make certain the code and software application were functional and secure, I manually reviewed the refactored code and performed static analysis with OWASP Dependency-check to make sure no new vulnerabilities were introduced. I also tested the application to ensure that HTTPS is used.
# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Some resources and tools I used in the projects that might be helpful in the future include OWASP-Dependency-Check for identifying vulnerabilities, Java Keytool for generating and managing certificates, Spring Boot for building and running applications, and SHA-256 for checksum verification. 

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
From this assignment, I can show employers my ability to conduct vulnerability assessments, refractor code to implement secure coding practices, configure and test HTTPS, and use industry-standard tools like OWASP Dependency-Check and Java Keytool. 
