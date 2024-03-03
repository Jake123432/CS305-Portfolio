# CS305-Portfolio

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is attempting to modernize thier operations, speciifically when it comes to secure communcation, by adding a file verification step. They will use a checksum verification for data verification, so we added an encryption cypher, SHA-256 to modernize the companies software security needs properly. Artemis is looking for the best software security available, and using the industries best practices we can make this request a reality. 

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

Well I implemented a SHA-256 algorithm, to create assymetric encryption using a public and private key to access, next I used Mavens Dependency Checkers newest version 9.0.9, to potentially get rid of any outdated vulnerabilities patched by the new version,compared to the version used previously, 5.3.0. Keeping the POM.xml file up to date solves alot of dependencies that otherwise would have to be solved manually, it also does a better job of filtering out potential false positives. Software Security adds trust between the client and company that is offering a service. In artemis Financial's case, having secure communcation is a necessity since they will be working with clients personal and sensitive information, having good encryption and low collision is extremely useful. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

Well first, we started with an Authentication Certficate, which has information about me and the organization I work for, allowing me to secure my local host or website. Next we used a checksum verification to confirm that our cipher is secure. Next we used our Maven depedency checker to see the potential vulnerabilities in the code, and solutions for the potential vulnerabilities. I would use Mavens dependency checker in the future to assess vulnerabilities, as it is industry standards, and reliable, if you ensure you elimiate all potential false-positives. 

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
Using our different methods, with the checksum verification, ensuring no logical or syntactical errors arrised within my code, and using the maven dependency check report to decide what vulnerabilities existed. I created a new Depedency check report after I refactored the code to see if any new vulnerabilities presented themselves, and if they did I changed parts of the code to match the security of the software that was requested by artemis Financial. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I would say all of the above, checksum verifcation is extremely important for securing a host of a website, paired with an Authentication Certificate to verify the host of the website. Next using a Maven Dependency Checker plugin within the POM.xml file to give us a report of potential vulnerabilities, to assess and eliminate as many as possible, specifically dependency vulnerabilities. The flow diagram presented was also extremely helpful with knowing what is expected of the code, and how to create code based around secure measures. 

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
Well I would show them first my SHA-256 encryption cypher, and also my familiarity with depedency checks and understanding how to properly update the pom.xml file. In this assignment, we did not do this, but being able to identify false-positives, and suppressing them to stop potential waste of time on parts of the code that are already secure.
