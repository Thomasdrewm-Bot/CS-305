Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a consulting company that develops financial plans for their customers. They want to mdoernize their operations to work on a web application based surface and therefore they need proper security and protocols to protect their clients' private information. They wanted to add a file verification step in their web application to ensure secure communications.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I implemented the checksum verification fairly well by scrambling the data string properly and showing clearly that the data string was properly scrambled using the appropriate alogrithm that was secure and has virtually no collision potential. It's important to code securely because it ends up costing a lot more money to go back and fix the entire code base to be secure after the fact of its implementation. Far more cost effective to do the secure coding as you code in the first place. Not to mention the possibility of omission of code due to "missing" portions of it. Software security adds a certain peace of mind to a comapny, giving them more credibility for others to trust them with their more sensitive information and tasks.

What part of the vulnerability assessment was challenging or helpful to you?

The most challenging part for me was trying to figure out which vulnerabilities meant what and having to inerpret what each one meant.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased the layers of security by making sure that the application would scramble the information with an algorithm that resulted in virtually no collisions and also making sure that hte ewebsite would use certificates to authenticate the web server that someone was accessing as well. Using the report it tells you what can or can not be fixed and based on that information alone you can find fixes just by going and updating the libraries that you're using to create the program.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

Running the program was the way to make sure that it was functional. Security was handled by uploading the certificate and seeing if the website would recognize that there was one, the smae one that I created. Also checking the vulnerability report and minimizing the potential for the code to fall into the trap of those vulnerabilities. After refactoring the code you had to run the report again to make sure that there were no changes to the vulnerabilities to make sure that you didn't introduce new ones into the code.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Learning more about the various security measures can be useful to future projects in the essence of keeping things consistent in the way I code. Making sure that I try to code securely on a regular basis to make it more of a 'habit.'

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would show them how I redid the code in order to scramble the data with an algorithm and show them that I can perform at least this basic function of software security.
