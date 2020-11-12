# Javascript

## How javascript makes web pages more interactive

1. Access Content

1. Modify Content

1. Program Rules

1. React to events

## A script is a series of Instructions

Scripts are made up of instructions a computer can follow step-by-step. A browser may use different parts of the script depending on how the user interacts with the web page. Scripts can run different sections of the code in response to the situation around them.

## Writing a Script

Start with the big picture of what you want to achieve, and break it down into smaller steps.

1. Define the goal

1. Design the scrip

1. Code each step

## From steps to code

- **Vocabulary** are the words that the computer understands

- **Syntax** is how you put those words together to create instructions the computer can follow

- Often scripts will need to perform different tasks in different situations. You can use flow charts to work out how the tasks fit together. Flowcharts show the paths between each step.

## Expressions

An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions.

1. Expressions that just assign a value to a variable

1. Expressions that use two or more values to return a single value

## Operators

Expressions rely on things called **operators**; they allow programmers to create a single vallue from one or more values. (=,+,*,<,>)

### Arithmetic Operators

JS contains the following mathematical operators which you can use with mumbers:

- `+` adds

- `-` subtracts

- `/` divides

- `*` multiplies

- `++` adds one to the current number

- `--` subtracts one from the current number

- `%` divides two values and returns the remainder

### String operator

There is just one string operator: the `+` symbol. it is used to joing the strings on either side of it.

## Functions

Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements)

### Declaring a function

```javascript
function sayHello() {
    document.write('Hello!');
}
```
Having declared the function, you can then execute all of the statements between its curly braces with just one line of code. this is known as **calling the function** You can call the function as many times as you want in the same JS file.

```javascript
sayHello();
```

### Declaring functions that need information

Sometimes a function needs specific information to perform its task. in such cases, when you declare the function you give it **parameters**. inside the function, the parameters act like variables.

```javascript
function getArea(width, height) {
    return width * height;
}
```

When you call a function that has parameters, you specify the values it should use in the paranthesis that follow its name. The values are called **arguments** and they can be provided as values or variables.

[back to README](README.md)