# SNHU_CS-305_Software_Security

# Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
In this project I worked for a client, Artemis Financial. Artemis Financial is a company in the financial industry, which required a security upgrade to their application. They needed an encryption algorithm to send data, and they wanted their application to use HTTPS for a secure connection.

# What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I feel that I was able to sift through various algorithms and choose the one that best fit Artemis's needs. Keeping vulnerabilities in mind when developing is important. We can keep applications secure and up-to-date by patching security holes, and we can find these holes via manual inspection and using tools like the Maven Dependency Check. Coding securely not only protects the users' sensitive data, it can also protect the company from fines due to regulations.

# What about the process of working through the vulnerability assessment did you find challenging or helpful?
The most challenging part of the vulnerability assessment was understanding what were false positives, and what were actual vulnerabilities. I tried to stay on the safe side by not suppressing any vulnerabilities I wasn't sure about. That being said, it was great to learn about the vulnerability database, which allowed me to patch or be aware of possible vulnerabilities.

# How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
I had to search for the right algorithms to secure sensitive data. I utilized the Java keytool with the RSA algorithm to create private and public keys, and then added those into the application. In the future, I would continue to use the dependency checker and ensure dependencies are up-to-date. Along with this, I would use HTTPS along with encryption algorithms to secure sensitive data.

# How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
I would first compile the code and check for any errors in the IDE. If any were found, I would address them to get the application running. I would then run the Maven Dependency Check to view vulnerabilities with the dependencies in use. Most of the time, a dependency version change was necessary. After making changes to the code I'd rerun the Dependency Check and update as necessary.

# What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
Understanding how to create self-signed certificates for development purposes was very helpful. I also found the Maven Dependency Check to be an awesome tool, which took out a lot of manual work.

# Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
As a whole, I feel that my project showcases my understanding of secure coding, creating encryption keys and understanding different algorithms, and using tools to patch applications.
