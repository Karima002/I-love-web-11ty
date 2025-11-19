# Javascript: The Good Part


## Chapter 1. Good Parts
-  Most programming languages contain good parts and bad parts.
- The amazing thing about JavaScript is that it is possible to get work done with it without knowing much about the language, or even knowing much about programming.

## Analyzing Javascript
- JavaScript has a very powerful object literal notation. Objects can be created simply by listing their components. This notation was the inspiration for JSON, the popular data interchange format.
- "Why should I use JavaScript?" There are two answers. The first is that you don't have a choice. The other answer is that, despite its deficiencies, JavaScript is really good.
-  Throughout the book, a method method is used to define new methods. This is its definition:

``` JS
Function.prototype.method = function (name, func) {
    this.prototype[name] = func;
    return this;
};
```

## Chapter 2. Grammar
### Whitespace
- JavaScript offers two forms of comments, block comments formed with /* */ and line-ending comments starting with //

### Names
- A name is a letter optionally followed by one or more letters, digits, or underbars.
- Names are used for statements, variables, parameters, property names, operators, and labels.


### Numbers
- JavaScript has a single number type.
- 1 and 1.0 are the same value.
- Negative numbers can be formed by using the - prefix operator.
- The value NaN is a number value that is the result of an operation that cannot produce a normal result.
- The value Infinity represents all values greater than 1.79769313486231570e+308.

### Strings
- A string literal can be wrapped in single quotes (') or double quotes ("). It can contain zero or more characters.
- Strings have a length property. For example, "seven".length is 5.
- it is easy to make a new string by concatenating other strings together with the + operator. 
```JS
'c' + 'a' + 't' === 'cat'
```

### Statements
- The var statement declares a variable or variables, and can be used to define identifiers and assign values to them. When used inside a function, the var statement defines the function's private variables. 
``` Js
function myFunction() {
  var privateVariable = "private";
}
```
- A block is a set of statements wrapped in curly braces. 
- Here are the falsy values: false, null, undefined, The empty string '', The number 0, The number NaN
- If the condition is falsy, the loop breaks.
- The try statement executes a block and catches any exceptions that were thrown by the block. The catch clause defines a new variable that will receive the exception object.
- The return statement causes the early return from a function. It can also specify the value to be returned. If a return expression is not specified, then the return value will be undefined.




