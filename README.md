CS-305

Artemis Financial is a financial services company that needed to strengthen its software security to protect client information. Their primary requirement was to ensure secure communication between their application and clients,
specifically by moving from HTTP to HTTPS with an SSL keystore and refactoring their code to eliminate vulnerabilities. As part of this, I reviewed their existing application and implemented industry best practices to ensure compliance
with software security standards.

One of the things I think I did really well was identifying and addressing software security vulnerabilities through manual review and static testing. For example, I had to ensure that HTTPS was enforced using SSL certificates and that
cryptographic hashing with SHA-256 was applied to protect the integrity of transmitted data. Coding securely is very important because it protects client information from unauthorized access and reduces risks from data breaches and legal
or regulatory issues. Software security adds value by maintaining client trust and ensuring long-term business stability.

The vulnerability assessment process was challenging and helpful. It required carefully reviewing the application's architecture, error handling, and cryptographic use while verifying that no new vulnerabilities were introduced during refactoring.
I increased layers of security by enforcing encrypted communication, using industry standard secure coding practices, and validating data integrity. To verify functionality and security, I ran the refactored code in Eclipse, performed static testing
with the OWASP Dependency-Check tool, and confirmed that the application executed without any errors. Resources like Spring Boot's SSL configuration, dependency-check, and secure coding guides will definitely be useful in my future projects. For future
employers, I could show this project as an example of how I was able to identify vulnerabilities and validated that software remained functional and secure.
