 ## Error Handling and Debugging
 ![debugging](https://jesusheredia.info/sites/default/files/styles/teaser/public/field/image/error.jpg?itok=VBKQsAHS)

 order of execution order in which statements are processed
execution contexts one global execution context and each function creates a new execution context
the stack JS terp processes on line at a time, stacks new function on top of current task
execution context & hoisting when script enters new execution context
prepare
new scope created
variables, functions, arguments created
execute
assign values to variables
reference functions and run code
execute statements
lexical scope linked to object they were defined within
exception JS statement error causes, terp stops and looks for exception-handling code
error object shows information about error
dealing with errors
debug script
handle errors gracefully(error handling code)
broswer dev tools JS console
console object
log data to console
console.log
console.info
console.warn
console.error
console.group
console.tab
console.assert
breakpoints pause execution of script on any line
stepping over breakpoint passes over functions, can step into functions
conditional breakpoints specify condition to trigger
debugger keyword creates breakpoint
handling exceptions
try specify the code that you think might throw an exception in the try block
catch if try code blocks throws exception catch steps with an alternative code set
finally will run whether try block succeeds or fails
throwing errors create your own error before interpreter creates them
