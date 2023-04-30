## What is functional programming?
A programming paradigm where functions are the primary building blocks of a program. It emphasizes the use of pure functions, immutability, and avoiding side effects to make the code more predictable and easier to understand.
## What is a pure function and how do we know if something is a pure function?
A pure function is a function that:

- Always produces the same output for the same input.
- Has no side effects, meaning it doesn’t modify any external state or data.

To identify a purse function, check if it meets both criteria.
## What are the benefits of a pure function?
- Predictibility: They always produce the same output for the same input.
- Easier to understand and reason about: No side effects to worry about.
- Easier to test: no need to set up or manage external states.
- Facilitates parallel and concurrent execution: Pure functions don’t modify shared resources, reducing potential issues.
## What is immutability?
Immutability means that once an object or data structure is created, it cannot be changed. Instead of modifying the existing object, a new object with the desired changes is created. Immutability helps prevent unintended side effects and makes the code more predictable.
## What is Referential transparency?
A property of a function that means it can be replaced with its output value without affectinig the program’s behavior. This occurs when a function is pure and only depends on its own input. Referential transparency makes it easier to understand, reason aboout, and optimize the code.
## What is a module?
A module is a piece of code that is organized into a separate file or a group of related files. It encapsulates related functions, classes, or variables, and can be imported and used in oother parts of a program. Modules help make the code more organized, maintainable, and reusable.
## What does the word ‘require’ do?
require is a function in some programming languagese, such as JS that is used to import a module into the current file. It allows you to access the functions, classes, or variables defined in the imported module and use them in your code.
## How do we bring another module into the file the we are working in?
To bring another module into the file you are woorking in, you typically use the import or require function (depending on the programming language). you provide the module’s file path or name as an argument, and the function returns an object containing the module’s exported members.
## What do we have to do to make a module available?
To make a module available for other files to use, you need to export the functions, classes, or variables you want to share. This is usually done using the export keyword or by assigning the module’s public members to an object.
