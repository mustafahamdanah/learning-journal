## Functions/methods/objects

- Functions allow you to group a set of related
statements together that represent a single task.

- Functions can take parameters (informatiorJ required
to do their job) and may return a value.

- An object is a series of variables and functions that
represent something from the world around you.

- In an object, variables are known as properties of the
object; functions are known as methods of the object.

- Web browsers implement objects that represent both
the browser window and the document loaded into the
browser window.

- JavaScript also has several built-in objects such as
String, Number, Math, and Date. Their properties and
methods offer functionality that help you write scripts.

- Arrays and objects can be used to create complex data
sets (and both can contain the other). 

## COMPARISON OPERATORS

- You may be familiar with comparison operators from math class. Let’s make sure there aren’t any gaps in your knowledge.

- less than (<) — returns true if the value on the left is less than the value on the right, otherwise it returns false.
- Greater than (>) — returns true if the value on the left is greater than the value on the right, otherwise it returns false.
- Less than or equal to (<=) — returns true if the value on the left is less than or equal to the value on the right, otherwise it returns false.
- Greater than or equal to (>=) — returns true if the value on the left is greater than or equal to the value on the right, otherwise it returns false.
- Equal to (===) — returns true if the value on the left is equal to the value on the right, otherwise it returns false.
- Not equal to (!==) — returns true if the value on the left is not equal to the value on the right, otherwise it returns false.

### LOGICAL OPERATORS

- Comparison operators allow us to assert the equality of a statement with JavaScript. For example, we can assert whether two values or expressions are equal with ===, or, whether one value is greater than another with >.

- There are scenarios, however, in which we must assert whether multiple values or expressions are true. In JavaScript, we can use logical operators to make these assertions.
- && (and) — This operator will be truthy (act like true) if and only if the expressions on both sides of it are true.
- || (or) — This operator will be truthy if the expression on either side of it is true. Otherwise, it will be falsy (act like false).

## loop

- Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript.

### for statement
* A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

* A for statement looks as follows:

- for ([initialExpression]; [condition]; [incrementExpression])
statement

### do...while statement
* The do...while statement repeats until a specified condition evaluates to false.

* A do...while statement looks as follows:

- do
    statement
  while (condition);

### while statement

* A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

- while (condition)
   statement