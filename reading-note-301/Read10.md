#  In memory storage

+ What is a ‘call’?

A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function.


+ How many ‘calls’ can happen at once?

One by one.

+ What does LIFO mean?

When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

+ Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

unction firstFunction(){

console.log(“Hello from firstFunction”);

}

function secondFunction( ) {

firstFunction( );

console.log( “The end from secondFunction”); }

secondFunction( );

+ What causes a Stack Overflow?

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.


## JavaScript error messages

+ What is a ‘refrence error’?

This is as simple as when you try to use a variable that is not yet declared you get this type os errors

+ What is a ‘syntax error’?

This is as simple as when you try to use a variable that is not yet declared you get this type os errors.


+ What is a ‘range error’?

It is thrown when trying to pass a value as an argument to a function that does not allow a range that includes the value

+ What is a ‘tyep error’?

It is an error that show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

+ What is a breakpoint?

It is the place where code execution can be stopped.

+ What does the word ‘debugger’ do in your code?

The debugger keyword stops the execution of JavaScript, and calls (if available) the debugging function.
