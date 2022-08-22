# Artemis


Briefly summarize your client, Artemis Financial, and their software requirements. 

Who was the client?
Artemis Financial

What issue did they want you to address?
They wanted me to provide an in-depth security analysis of their code-base.

What did you do particularly well in identifying their software security vulnerabilities? 
I provided a clear and concise recommendation for which cryptographic algorithms to use and why.  They were not using
SSL/TLS or any type of data integrity check API.

Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
Data integrity is paramount to the success of any organization.  If you don't code securely you leave yourself open to
ethical and legal rammifcation. For example:  Loss of PII data.  There could be a major multi-suit litigation brought against you for this.

What about the process of working through the vulnerability assessment did you find challenging or helpful?
I found the most helpful part was integrating and doing in-depth analysis of the java keytool.

How did you approach the need to increase layers of security? 
I began by identifying where the software had vunerabilities, and proceeded to implement new ways to defend against potential cyber threats.

What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
I plan on using the maven dependency check tool alot more often to define what areas are most concerning.

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
I ran a security check before I implemented new code, and another after.  I found that vunerabilities decreased.  I ran in-line unit tests to confirm code was working
as intended.

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
I will continue to use the maven platform to perform testing and dependency security verification.

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
I already work in the industry as an engineer, but I believe the final project would be best to show to a future employer.
