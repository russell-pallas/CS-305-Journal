# CS-305-Journal

Artemis Financial is an international financial institution who was in need of an updated program. They were in need of security features being added to the program to keep them in line with current standard practices. 

Security in an institution's software is essential to them doing well and proper business. Customers should know that their information and financials are secure within the institution's hands. Without proper security, a company opens themselves up to loss of business as well as litigation. I found that many of these instances of security failing within the software came with vulnerabilities in the dependencies. I found that I did well at implementing and using the OWASP plugin to identifiy these security vulnerabilities and take proper action. 

The most challenging part of the vulnerability assesment that I found was thinking critically and thinking about the big picture within the software as well as how recommendations here would impact the software itself. 

I found that the best way to increase the layers of security within the software was to ensure that one layer did not directly depend on the other. There were many vulnerable dependencies within this program. I also found that there is such thing as too much security. You do not want a program that even you have trouble accessing under normal use. 

Running the program showed that there were no issues or errors with the program and that it ran as expected. However, after refactoring, we needed to ensure that there weren't any new vulnerabilities introduced. We made sure that there weren't any new vulnerabilities introduced by rerunning the OWASP plugin and ensuring that the number of vulnerable dependencies did not increase. 

I found that most useful practice that I used was reading through all of the code becasue it allowed me to see how all of the different parts of the program worked together with each other. I also found that the owasp plugin was a major help to see the areas of vulnerability as well as the various features that the program was using. 

Employers tend to look for areas where an employee can create an efficiency. I found that the best way to make this more efficient was to remove the false positives from the OWASP report. I think that I would show them the removal of the false positives and show that we could save some time to fix the vulnerabilites and get a deliverable to customers sooner. 
