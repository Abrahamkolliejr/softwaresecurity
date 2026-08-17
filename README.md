# CS 305 Portfolio Reflection

## Briefly summarize your client, Artemis Financial, and its software requirements.

Artemis Financial was the client for this project. The company works with financial information, including customer accounts, savings plans, retirement information, investments, and insurance records. The company wanted its software to be more secure and protect private customer information. My job was to look for security problems in the application and recommend ways to fix them.

## What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely?

I think I did well at reviewing the code and finding different security problems. Some of the problems I found included hard-coded database login information, database connections that were not closed, and error messages that could show too much information. I also found problems with missing authentication, input validation, and access control.

Secure coding is important because companies need to protect their customers and their information. Good software security can help prevent data breaches, protect the company's reputation, and make customers feel safer using the application.

## Which part of the vulnerability assessment was challenging or helpful to you?

The most challenging part for me was understanding the dependency-check results and figuring out which vulnerabilities were important. It was also one of the most helpful parts because it showed me that security problems can come from libraries that developers did not personally write. For example, the project used older versions of Spring Boot and Bouncy Castle that needed to be updated.

## How did you increase layers of security?

I recommended adding more layers of security by using authentication, role-based authorization, input validation, secure database connections, and better error handling. I also recommended using HTTPS and updated TLS settings to protect information while it travels between the user and server. In the future, I would use tools such as OWASP Dependency-Check along with manual code reviews and security testing to find vulnerabilities and decide how they should be fixed.

## How did you make certain the code and software application were functional and secure?

I used both manual review and dependency scanning to look for security problems. After making security changes, I would test the application again to make sure it still works correctly and run another dependency check to see if any new vulnerabilities were introduced. Testing after updates is important because fixing one problem can sometimes create another problem. The security plan also recommended running dependency scans and tests during every build.

## What resources, tools, or coding practices did you use?

Some helpful resources and tools from this project were Maven, OWASP Dependency-Check, Java, Spring Boot, and vulnerability databases. I also learned about secure coding practices such as input validation, encryption, HTTPS, secure error handling, access control, and keeping dependencies updated. These are skills and tools that I can use again in future classes and software development projects.

## What might you show future employers from this assignment?

I would show future employers my Artemis Financial Vulnerability Assessment Report. This project shows that I can review software for security problems, identify vulnerabilities, and recommend ways to make an application safer. It also shows that I understand that software development is not only about making a program work. Developers also have to think about protecting users and their information.
