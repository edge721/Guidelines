# Guidelines
NodeJs Guidelines Fresher/Intermediate

# Development Guidelines:

Need to log technical changes over confluence and need to notify team (Frontend team only accept change only if it is mentioned in confluence) <br /> 
There must 4 branches during development <br /> 
Dev : For internal development <br /> 
Qa: For QA testing <br /> 
Staging: To be sent to client <br /> 
Master: production <br /> 

We would have 4 separate deployments for each branch. <br /> 
There is at least one code reviewer for any merge over dev branch <br /> 
QA and Staging branch will only be merged by tech lead(Either internal or Client side) <br /> 
A linter passing code will only be eligible for pull request (Reviewer will responsible for that) <br /> 

# Process flow for New Fresh/Intermediate Joiners

# Documenting better
Try to document every module with relevant information about the module like what it does and who wrote it <br /> 
Try to document all functions with their input and output parameters <br /> 
Try including a header to give out important information about the file/module as to what goes in there. <br /> 

# Indentation and Naming standards
There must be a space after giving a comma between two function arguments. <br /> 
Each nested block should be properly indented and spaced. <br /> 
Proper Indentation should be there at the beginning and at the end of each block in the program. <br /> 
All braces should start from a new line and the code following the end of braces also start from a new line. <br /> 
Meaningful and understandable variables name helps anyone to understand the reason of using it. <br /> 
Local variables should be named using camel case lettering starting with small letter (e.g. localData) <br /> 
Global variables names should start with a capital letter (e.g. GlobalData). <br /> 
Constant names should be formed using capital letters only (e.g. CONSDATA). <br /> 
It is better to avoid the use of digits in variable names. <br /> 
The names of the function should be written in camel case starting with small letters. <br /> 
The name of the function must describe the reason of using the function clearly and briefly. <br /> <br /> 

# Controllers and Services
Controllers should only contain direct request interfaces and should not have any business logic. <br /> 
Further processing may be done by calling one or more functions from respective service files.  <br /> 
Functions inside of services may not be very long and if required, broken into other smaller reusable functions for enhanced modularity.  <br /> <br /> 

# Exceptions handling
Exceptions thrown must be caught and formatted before ending the response to maintain uniformity. <br /> <br /> 

# Writing Test cases
One should write test cases along with code and make it a practice as it greatly improves ones efficiency at quality of code being written. <br /> 
A test framework can be used to go about the whole process of developing a test oriented programming. <br /> 

