# CS-305




Project Summary
Artemis Financial is a financial services company that specializes in providing individualized financial planning to its customers. The company required a secure baseline for its web application to safeguard sensitive customer financial data and protect its software architecture from unauthorized access. To address these needs, I conducted a comprehensive vulnerability assessment and refactored the existing software application to implement robust, secure programming practices. I successfully identified weak cipher suites and outdated dependencies while implementing strong cryptography to secure their data transmission.

Vulnerability Assessment & Mitigation
During the assessment, I excelled at utilizing automated scanning tools to efficiently locate hidden vulnerabilities within the application's dependencies. Managing and analyzing false positives within the static analysis reports proved to be both a challenging and helpful exercise, as it taught me how to prioritize critical risks without wasting development time. To add multiple layers of security to the application, I implemented HTTPS with TLS 1.3 protocol restrictions, enforced strong encryption algorithms, and added strict input validation. In future projects, I plan to utilize automated tools like OWASP ZAP for dynamic scanning and Dependency-Check integrated directly into CI/CD pipelines to continuously assess risks and decide on mitigation techniques.

Secure Coding Practices
Coding securely is vital because it proactively defends software against malicious exploits, protects sensitive user data, and ensures compliance with financial regulations. Software security adds immense value to a company's overall well-being by reducing legal liabilities, preventing catastrophic financial losses from data breaches, and maintaining customer trust. To guarantee that the application remained fully functional after these security enhancements, I executed comprehensive unit test suites to verify that the business logic was intact. After refactoring the code, I re-ran Static Application Software Testing (SAST) tools to perform regression testing and confirm that no new vulnerabilities were introduced. Helpful tools and resources from this project that I will use in future tasks include the Java Cryptography Architecture (JCA), Maven dependency plugins, and SpotBugs.

Employer Takeaways
This assignment serves as an excellent portfolio piece to showcase to future employers because it demonstrates my practical, hands-on skills in threat modeling, risk mitigation, and cryptographic implementation. By presenting this artifact, I can prove to hiring managers that I possess the technical knowledge required to identify software gaps and successfully bridge the divide between theoretical security policies and functional, secure code execution.
