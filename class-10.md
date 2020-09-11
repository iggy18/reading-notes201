# chapter 10
## error handling and debugging

- order of execution the order in which staements are excuted can be complex. some tasks can not be completed until another function has run.
- execution context cover the scope of which a variable can be used.
- execution context and hoisting
1. preare - the new scope is created
2. variables functions, and arguments are created.
- execute
1. now it can assign values to variables
2. reference functions and run thier code
3. execute statements

**Scope**
each execution context has its own variables object. children can accesss the parents funtions and variables, but parents cannot access the child functions and variables.

**error objects**

***property descriptions***
when and error object is created it will contain the following properties.
name -type of error
message - description
filenumber - name of the javascript file
line number - line number of error

***object desriptions***
error -geric error, all others are based on this error
syntax error - syntax has not been followed
reference error - tried to reference a variable that is not declaired
type error - unexpected data type that can not be coerced
range error - numbers not in accesable range
uri error - encode and decode methonds used incorrectly
eval error - eval function used incorrectly


### debuigging workflow
**where is the problem?**
narrow down the area where the problem seems to be
look at the error message 

**what exactly is the problem?**
break down/break out parts of the code to test in smaller pieces

if you know your code might fail use try, catch, and finally.

