# CS305-Software-Security

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a financial institution that was looking to modernize their practices and general operations. They hired our company to apply current software security standards to protect their software from potential and current cyber threats.

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I really enjoyed static testing, and found it to be easy to implement and perform. While it doesn't innately filter out false positives, it is not hard to add a file to ignore specific items. Securing code is important for protecting users and their information, as well as the institution, from cyber attacks and compromised data. By adding these security measures, you ensure that all information is secure and the trust users put in a company isn't misplaced.

What about the process of working through the vulnerability assessment did you find challenging or helpful?
The dependency check tool was extremely helpful in identifying weaknesses in code as well as being able to identify false positives. The ability to export xml code to suppress false positives also allowed for being able to hyperfocus on what potential issues were vulnerable.

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
The first test was to see what dependencies were vulnerable through the dependency check. Most of what was found was related to versions being out of date. Keeping dependencies checked and updated is the main step to mitigate. Similarly, regular code reviews can help spot weaknesses due to outdated code and allow for new fixes to be applied.

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
Running a debug when making changes can help in making sure code is functional. Periodically running dependency checks and checksums can reveal added vulnerabilities. When refactoring code it is crucial to run a dependency check to ensure no new vulnerabilities have been added. 

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
I encountered a few issues with the dev environment, and errors I had never encountered before. Using resources such as Reddit and StackOverflow can provide a wealth of information to similar issues that others have encountered, allowing for a potential quick fix as well as understanding behind the fix. Reading the general discussion forum on the class page gave me some solace that some issues I was having were not just specific to me and seeing things worked through and figured out helped not only with the coursework but also with seeing the class (or team) work together to solve one person's issue.

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
From the submitted assignment, I feel I performed strongly in interpreting the needs of the client as well as being able to quickly identify faulty code from a glance in section 3. Granted some of it said FIXME, being able to identify problem areas early is beneficial in the longrun. Analyzing dependency checks for false positives and discerning what could be a potential non-issue for the client saves time and resources.
