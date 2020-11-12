# Loops

## Comparison Operators: Evaluating Conditions

`==` is equal to

`!=` is not equal to

`===` strict equals to

`!==` strict not equals to

`>` greater than 

`<` less than

`>=` greater than or equal to

`<=` less than or equal to

### Structuring Comparison Operators

```javascript
(score >= pass)
```

### Using expressions with comparison operators

```javascript
((score1 + score2) > (highScore1 + highScore2))
```

The operand does not have to be a single value or variable.

## Logical Operators

`&&` logical and

`||` logical or

`!` logical not

```javascript
((5 < 2) && (2 >= 3))
```

Tests more than one condition to make sure both are true. both sides above are `false` and `false`

## Loops

### For Loops

For loops are if you need to run a loop of code for a specific number of times.

### while Loops

While loops are for if you do not know how many times the code should run

### do while

Do while loops are very similar to while loops but will run the statements inside the curly braces at least once, even if the condition evaluates to false.

```javascript
for (let i = 0; i < 10; i++) {
    document.write(i);
}
```

## Loop counters

### Initialization

`var i = 0;` Create a variable and set it to 0. this variable is commonly called i and it acts as the counter

### Condition

`i < 10;` The loop should continue to run until the counter reaches a specified number.

### Update

`i++` Every time the loop has run the statements in the curly braces, it adds one to the counter.

[back to README](README.md)