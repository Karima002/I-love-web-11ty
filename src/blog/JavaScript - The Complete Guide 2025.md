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
