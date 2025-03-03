### **README File Update for Artemis Financial Security Portfolio**

#### **1. Client Summary**
Artemis Financial is a financial services company that offers a variety of products to businesses and individuals. The company needed assistance in securing their web application to ensure safe and encrypted data transmission for their users. Their primary goal was to enhance security by identifying vulnerabilities within their software and implementing best practices for secure coding, particularly focusing on encryption, secure communication, and reducing exposure to potential threats.

#### **2. Software Security Vulnerabilities - What Went Well**
When addressing Artemis Financial's software security vulnerabilities, the most significant achievement was implementing **AES encryption** for secure data transmission and ensuring data integrity using **checksums**. I used tools like the **OWASP Dependency-Check** to perform a thorough static analysis of their codebase and identify potential vulnerabilities. **Coding securely** is crucial because it prevents unauthorized access, protects sensitive information, and ensures the integrity of data. Secure code practices not only minimize risks from malicious attacks but also enhance a company's reputation and trustworthiness, ultimately contributing to its **long-term success** and **legal compliance**.

#### **3. Challenges in the Vulnerability Assessment**
The most challenging part of the vulnerability assessment was **configuring the OWASP Dependency-Check tool** to handle false positives and ensuring that the right dependencies were flagged. Additionally, configuring the correct **HTTPS settings** to secure the communication between the application and the users proved to be a meticulous task, especially when dealing with the self-signed certificate. However, this was also one of the most helpful experiences because it strengthened my understanding of web application security.

#### **4. Increasing Layers of Security**
To increase security, I added layers like **AES encryption** to protect sensitive data and ensured the integrity of that data with **SHA-256 checksums**. Additionally, I implemented **HTTPS** to ensure that data transmission was encrypted over the network. Moving forward, I would use more advanced vulnerability scanning tools, such as **OWASP ZAP** or **Burp Suite**, for dynamic analysis. Deciding on mitigation techniques would depend on the specific vulnerabilities identified, but patching outdated dependencies and configuring secure communication protocols like **TLS 1.2** would always be prioritized.

#### **5. Ensuring Code and Software Security**
After refactoring the code to remove security flaws, I verified the application’s functionality and security by performing both **static testing** and **functional testing**. I used tools like **OWASP Dependency-Check** to assess external libraries for vulnerabilities, and I manually tested the encryption/decryption mechanisms to ensure they were working as intended. Additionally, I ensured the proper configuration of **SSL certificates** and conducted functional tests to verify the web application was accessible securely over HTTPS.

#### **6. Resources, Tools, and Coding Practices**
I utilized several resources and tools in this project that will be valuable for future assignments:
- **OWASP Dependency-Check** for identifying vulnerabilities in external libraries.
- **Maven** for managing project dependencies.
- **AES/CBC/PKCS5Padding** for encryption and **SHA-256** for checksums.
- **Keytool** to generate the self-signed certificates and manage the keystore.

Using these tools and coding practices helped ensure that the application met the highest security standards, and these will be useful in tackling similar tasks in the future.

#### **7. Employer Showcase**
For future employers, I would highlight this project as an example of how I can identify and mitigate security vulnerabilities in real-world applications. Specifically, I would demonstrate:
- How I conducted a **vulnerability assessment** and implemented security best practices.
- The process of refactoring code to enhance security while ensuring the application remained functional.
- My experience in implementing **encryption** techniques and securing **data transmission** via **HTTPS**.

This would showcase my ability to apply security practices in software development and demonstrate a **proactive approach to addressing vulnerabilities**.

---

