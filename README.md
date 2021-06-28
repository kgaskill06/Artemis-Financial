# Artemis-Financial

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial was the client and they aimed to improve their software by adding additional security features for their web application. Their web application was used to transfer data and they wanted a data checksum verification implemented to their security protocols. 

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I feel I did well in identifying vunerabilities but there is definitely room for improvement as this was my first attempt at using OWASP and targeting known vunerabilities. It is important to code securely as it helps fight against cyber terrorists/hackers that want to exploit vunerabilities. In addition to securely protecting your data, it helps build consumer trust as data leaks can make investors and consumers lose faith. 


What about the process of working through the vulnerability assessment did you find challenging or helpful?

The most challenging was identifying vunerabilities that were false positives and identifying ones that were truly a vunerability. I think what is somewhat more challenging is fixing the vunerability as it will require a lot of research and reading to find what the fix is because sometimes it is as easy as changing a version or it maybe an entirely different approach because a workaround is implemented until a version update.

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

A lot of reading was rather helpful in deciding what type of techniques I can use to create an additional security step. 

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

I utilized a checksum to verify the data was securely being exchanged through the messagedigest. After I refactor code, I would run maven OWASP dependency check to see if any new vunerabilities appeared. 

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

I found the typical websites like stackoverflow really beneficial when trying to read more into how some of these secure coding techniques worked. The website that tells you all the cipher algorithms is informative when listing names of ciphers but not very helpful describing how to implement. I have saved my lines of code to reuse in the future or refactor alter as I feel they are good at understanding the logic. It will also come in handy showing how a message digest cipher was used and showing how my checksum verification.
