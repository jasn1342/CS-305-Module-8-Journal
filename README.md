# CS-305-Module-8-Journal

### Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Aretemis Financial is an instituion that mananges personal finances for their clients in the form of savings, investment, retirement, and insurance accounts. They have hired our company, Global Rain, to develop an application that will allow their clients to upload files and access their accounts. One of the main concerns that Artemis Financila rightly has is security, specifically when it comes to the verification of data tranfers within the application.


### What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I believe I did well in using the Maven Dependency check to identify security vulnerabilities. For this particular project, updated the spring-boot-parent version reduced the number of detected vulnerabilities from 41 to 2, and the two that were detected were not considered serious vulnerabilities. I also created a checksum value using a secure cipher and hash algorithm. It is important to code securley because when confidential data is at stake, it needs to be secure and protected from attackers. Customers and clients place their trust in companies that will keep their data safe, so ensuring that software is secure will help to ensure that the company's well-being is also secure.


### What about the process of working through the vulnerability assessment did you find challenging or helpful?
The most challenging aspect of the vulnerability assesement was determining which dependencies the application was or was not using. This was important to know when evaluating which vulnerabilites were considered false positives. Updating the spring-boot-parent version to the most recent release definitely helped with narrowing this list of possible false positives down.

### How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
I approached the need to increase layers of security by using encryption and hashing algorithms to create a more securte application in addition to an SSL certifiacte and keystore to ensure that data tranferred within the application was secure. I also ensured that the application's dependencies were free of critical vulnerabilities using a vulnerability asessement. In the future, I will use these same techniques and do a manual code review to ensure that there are no vulnerabilities and if there are, I will use appropriate encryption and hashing algorithms to mitigate those vulnerabilites. 

### How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
I tested each aspect 


### What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?


### Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
