# CS_305_Software_Security

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a consulting company that develops individualized financial plans for its customers. Artemis Financial wanted us to assist in modernizing its operations. This included performing a vulnerability assessment of their existing RESTful API code to protect from exterenal threats as well as adding a file verification step to its web app to ensure secure communication in the form of a checksum.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

What I did well regarding the client's security vulnerability was utilizing the Dependency Check SAST tool to find known vulnerabilities and compiled them into one document for review. It is paramount to code securely and not merely as an afterthought. Any application that has any sort of connectivity with any entities outside of itself needs to have security be a primary concern. No matter the industry, there will be something of value that bad actors will want to access, whether it is financial information, heath information, or personal information, etc. A company with poor security opens itself up to being attacked, which can obviously cause them direct damages, but further, the users' trust in the company will erode and may be very difficult to get back.

Which part of the vulnerability assessment was challenging or helpful to you?

Utilizing the Dependency Check tool was very helpful to me. It forced me to familiarize myself with installing plugins and altering xml files as well as the obvious revealing of known security vulnerabilities.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased layers of security by referring back to the Vulnerability Assessment Process Flow chart included in our resources. Using these tenets of secure coding allowed me to focus on the most important aspects of keeping our application secure. Though all of the elements are important, for this particular application, focusing on input validation seemed to be the most crucial, and addressed most of the security issues. In the future I would still use the provided Vulnerability Assessment Process Flow chart to remind myself of what to focus on.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

With every change I made, I made sure to always run the code again and verify that it continues to run without errors. This is an effective way of ensuring changes I made did not introduce errors so that I can revert the changes if necessary. I also ran the Dependency Check tool before and after and made sure there were no additional vulnerabilities introduced.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

As mentioned, the Dependency Check tool was invaluable in this project. The Vulnerbility Assessment Process Flow chart also proved to be very useful to refer back to all throughout the class. This chart highlights secure coding practices that should be adhered to for future assignments or tasks.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would show employers my vulnerability assessment from Project One. This shows the valuable skill of reviewing code, both manually and using a tool such as the Dependency Check and my ability to compile that information into a digestible package to communicate the knowledge to technical and non-technical stakeholders alike.
