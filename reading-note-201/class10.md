# Error handling & debugging

debugging is the process of finding and resolving bugs (defects or problems that prevent correct operation)

*JavaScript interpreter uses the concept of execution contexts andEvery statement in a script lives in one of three of 
execution contexts*:
+ GLOBAL CONTEXT

- FUNCTION CONTEXT

About Stuck(by the way I'm alaways stuck) its happened when statement in function need data from another function

**Error object**
can help you find where your mistakes are and browsers have tools to help you read them.
example of these error :
 
+ Error ---> Generic error - the other errors are all based upon this error 

+ Syntax Error ---> Syntax has not been followed

+ TypeError ----> An unexpected data type that cannot be coerced  

**HOW TO DEAL WITH ERRORS**
1: DEBUG THE SCRIPT TO FIX ERRORS
2: HANDLE ERRORS GRACEFULLY

so we can use console to tell us when there is a problem It also displays the line 
where it became a problem ,The console helps narrow down the area in which the 
error is located, so you can try to find the exact error.

![console](https://qph.fs.quoracdn.net/main-qimg-29d506680f6e6477bc1a5ef0617f7fda)

+ JavaScript provides try-catch blocks to execute the code which is prone to error and may cause improper behaviour of the program. The finally block is 
placed after try and catch block and will be executed definitely in case any one of the blocks


try {
  adddlert("Welcome guest!");
}

catch(err) {
  document.getElementById("demo").

  innerHTML = err.message;
  
}

+ try statement allows you to define a block of code to be tested for errors while it is being executed.

+ catch statement allows you to define a block of code to be executed, if an error occurs in the try block.

+ finally statement lets you execute code, after try and catch, regardless of the result.



