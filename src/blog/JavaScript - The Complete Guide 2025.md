# Section 1: Introduction

### JavaScript in Action!
- Js: Dynamic, weakly typed programming language
- Interpreted compiled language
- Most prominent use-case: run code in a browser (on a webpage)
- Hosted language: runs in different environments (e.g. in browser)

### How JavaScript Is Executed
- If you write javascript code and you want it to have effect on the webpage. You need a javascript engine and its build into browser.
- The job of the engine is to read code (parse code), then compile it to machine code (reads code faster), then it excecute the code. The result is a effect on the webpage.

### Dynamic? Weakly types
- Dynamic, interpreted Programming Language: JS is "on the fly" compiled. That means that the code is ealuated and executed at runtime but also that the code can change at runtime. In that code you can do something that you are not allowed in other programming language. E.g. store a number in stead of a text in a variable.  
- Weakly Typed Programming Language: Data types are assigned to variables automatically. In JS you don't have to tell that this variable will hold a number. In other languages you need to tell the language that you will store a number.

### JavaScript Executes In A Hosted Environment
- JS runs on the browser-side but can also run on for example server-side.
- The Google's Javascript Engine was extracted to run Javascript anywhere called Node.js. Node.js can be executed on any machine and is therefore often used to build web backends (server-side JavaScript). Unlike client-side JS, Node.JS can access the local filestystem, inetract with the operating system. It can't manipulate HTML or CSS.

### Client-side (browser) vs server-sid (NodeJS)
- Client-side (browser): The orgin of Javascript. Allows interation with webpage and browser API. You can manipulate the loaded webpage.   
- Server-side (NodeJS): Use Javascript outside the browser. Allows for code & knowlegde reusage. Special non-browser APIs (e.g. to work with file system and incoming Http requests).

Syntaxt, concepts, core features etc. are exactly the same.

# Section 2: Basics: variables, Data types, Operators and Functions

### 19. Adding Javascript to the website
- `alert('This works!')`: Hiermee verschijnt een standaard layout pop up van de browser bij herladen.

### 20. Introducing variables & Constants
- In JS you can define a variable like this: `let userName = 'Max'`. A variable is a variable container that holds some data. `Max` is the value. You only write `let` by introducing the new value. A variable is a data container where the value can change.
- You can also define a variable with `const`. The difference is that you can't change the value, otherwise you'll get an error.
- Use `const` as often as possible (i.e. whenever you actually got data that never changes) to be clear about your intentions in your code.

### 21. Declaring & Defining Variables
- Allowed variable Naming: `let userName` = camelCase. See also [FDND code convention](https://docs.fdnd.nl/conventies.html#naamgeving). Other examples that are allowed: `ageGroup5`, `$kindOfSpecial`.
- Not allowed e.g. `user_name`, `21Players`, `user-b`, `let`. 
- Using ; is generally optional in JS.

### 22. Working with Variables & Operators



