# CS-305_Course
Portfolio for SNHU's CS-305 Software Security, taken March - April 2022, focused on learning how to develop secure code to meet security protocols. 

- *Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?*

The client company for this class was Artemis Financial, a financial consulting company that specializes in creating financial plans for individuals, with options ranging from investments, savings, insurance, and retirement for their customers. As part of a modernization effort, the company is developing new software, with myself helping to design and implement modern effective software security. 

- *What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?*

I am particularly proud of implementing the checksum verification with the keystore certificate. I struggled with this until it all came together and clicked. After trying many things and researching to figure out why I could not get it to work, I was able to figure it out and complete that task successfully. The checksum verification provides proof of secure communication between the client side to the server side. Secure communication is a key step in ensuring that data is not lost between the two. 

- *What about the process of working through the vulnerability assessment did you find challenging or helpful?*

I found the concepts of the vulnerability assessment challenging. All areas of the assessment are important, with them being more a part of the whole security of a project. While some projects may have some key vulnerabilities, ignoring any aspects of security could be a fatal flaw. 

- *How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?*

While no one layer of security is perfect, multiple layers allow the inevitable data breach to not be fatal to a company or its clients. I would like to explore the area of dependency management a bit more, as well as secure coding. Practicing code with security in mind seems like a great idea to consider security from the start of a project, instead of tacking it on later. Dependency management is an area that confuses me. On one hand, having dependencies that introduce security risks outside of one’s control seem like a blatantly bad security focuses, but at the same time using those dependencies allows for developers to build faster and better rather than trying to build everything from scratch. 

- *How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?*

After ensuring the code ran, followed secure coding practices, and had introduced no new errors with Eclipse, rerunning the OWASP dependency check was critical to discovering if new vulnerabilities existed. Comparing copies of previous dependency reports with the most recent shows no changes, and thus no new dependency vulnerabilities.  

- *What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?*

The OWASP dependency vulnerability tool is an interesting one I would like to explore more as I further research dependency management. I am curious to find out if that tool is the industry standard or if other tools exist. The creation of the SSL certificate is another thing I enjoyed. I am less familiar with that portion of code and app development and now that I have a taste of it, I am curious to learn more about it in the context of secure software development. 

- *Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?*

I will admit I enjoy the act of creating documents and reports. The Project Two document is one that I think perfectly encapsulates everything I learned in the class, alongside the skills learned during the class.  
