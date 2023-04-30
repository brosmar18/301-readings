## What is a `call`?
A `call` refers to the invocation or execution of a function or method in a program. When a function is called, the program starts executing the instructions within that function, and when the function is finished, the program returns too the point where the function is called.
## How many ‘calls’ can happen at once?
The number of calls that can happen at once depends on the program language and environment. In a single-threaded language like JavaScript, only one function call can be executed at a time. However, in multi-threaded languages or environments, multiple function calls can run concurrently.
## What does LIFO mean?
LIFO stands for Last in, First Out. It is a principle used in data structures, like a stack, where the last element added to the slack is the first one to be removed. This means that elements are processed in the reverse ordere of their arrival.
## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
main()           // First called
  ├─> funcA()    // Called from main()
  │     ├─> funcB()  // Called from funcA()
  │     └─> funcC()  // Called from funcA() after funcB() returns
  └─> funcD()    // Called from main() after funcA() returns
  In this example, main() is the first function called. Then, funcA() is called from main(), followed by funcB() and funcC() called from funcA(). Finally, funcD() is called from main() after funcA() returns.
## What causes a Stack Overflow?
A stack overflow occurs when the call stack exceeds its limits, usually due to excessive recursion or deeply nested function calls. When thee call stack is full, and an additional function call is attempted, a Stack Overflow error is thrown, indicating that the program has run out of stack space. This often leads to the program crashing or becoming unresponsive.

## What is a reference error?
A reference error occurs when a proram tries to access a variable or a function that has not been defined or is ouot of scope. It usually indicates that the code is referencing a nonexistent or mispelled variable or function name.
## What is a ‘syntax error’?
An error in the structure or grammar of the code. It oc curs when the program violates the rules of the programming language, such as missing parentheses, braces, or semicolons. Syntax errors prefvent the code from bing prooperly parsed and executed.
## What is a ‘range error’?
A range error occurs when a program tries to perform an opeeration with a value that is outside the alloawable range or domain for that operation. For example, a range error can happen when attempting to access an array element with an index that is negative or greater than that array’s length.
## What is a ‘type error’?
A type error occurs when a program tries to perform an operation with incompatible data types. For example, attempting to perform arithmetic opeerations on a string and a number or trying to call a non-function object as a function would result as a type error.
## What is a breakpoint?
A breakpoint is a marker set in the code to pause the execution of a program during debugging. When the program reaches a breakpoint, it stops, allowing the developr to inspect the current state of the program, examine variables, and step through the code to identify issues.
## What does the word ‘debugger’ do in your code?
The debugger keyword in your code is used to create a breakpoint programmatically. When the JS interpreter encounters the debugger keyword, it will pause the execution of the code if a debugging tool (such as a browser’s dev tools) is attached. This allows develoopers to inspect the program state, examine variables, and step through the code to indentify and fix issues.
