# Day 5 of Code Fellows

## Programming with JavaScript Notes

* **Control flow** is the order in which the computer executes statements in a script

* Use **conditional** structures or `if...else` so the code can execute depending on if the form is complete or not.

* Example of **control structures** include **conditionals**, **loops**, and **functions**.

* A **function** is a block of code that is designed to perform a particular task, and is executed when *something* invokes it.

* `function` is followed by a **name**, followed by parentheses **()**. An example would be `function exampleName(test1, test2, test3)`

* Function **parameters** are listed in the ().

* Function **arguments** are the **values** received by the function when it is invoked.

* The code inside the function will execute when something **invokes** the function: When an event occurs (clicking a button), when it is invoked (called) from JavaScript code, and automatically (self invoked).

* When the code reaches a `return` statement, the function will stop executing.

* Once invoked, the code will return to execute the code after the invoking statement.

* Loops helps reuse code so it can produce different results.

* The **assignment** operator `=` assigns a value to a variable.

* The **addition** operator `+` adds numbers

* The **multiplication** operator `*` multiplies numbers.

* The many types of JavaScript include: Arithmetic, Assignment, Comparison, Logical, Conditional, and Type Operators.

## Operators and Loops Notes

* **Assignment Operators** assigns a value to its left operand based on the value on its right operand.

* If an expression evaluates to an [object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects), then the left-hand side of an assignment expression may make assignments to properties of that expression.

* If an expression does not evaluate to an object, then assignments to properties of that expression do not assign.

* In [strict mode](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode#converting_mistakes_into_errors), the code throws, because one cannot assign properties to primitives.

* The **destructuring assignment** syntax makes it possible to extract data from arrays or objects using a syntax that mirrors the construction of array and object literals.

* A **Comparison Operator** compares its operands and returns a logical value based on whether the comparison is true, and it can be numerical, string, logical, or object values.

* The comparison operators are equal `==`, not equal `!=`, strict equal `===`, strict not equal `!==`, greater than `>`, greater than or equal `>=`, less than `<`, and less than or equal `<=`.

* A `for` loop repeats until a specified condition evaluates to false.

* When a `for` loop executes, the `initialExpression`, if any, executes. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables. The `conditionExpression` expression is evaluated. If the value pf `conditionExpression` is true, the loop statements execute. Otherwise, the `for` loop terminates. (if the `conditionExpression` expression is omitted entirely, the condition is assumed to be true). The `statement` executes. To execute multiple statements, use a **block statement** `({})` to group those statements. If present, the update expression `incrementExpression` is executed. Finally the control returns to the second step.

* A `while` statement executes its statements as long as a specified condition evaluates to `true`.

* If the `condition` becomes `false`, `statement` within the loop stops executing and control passes to the statement following the loop.

* The condition test occurs *before* `statement` in the loop is executed. If the condition returns `true`, `statement` is executed and the `condition` is tested again. If the condition returns `false`, execution stops, and control is passed to the statement following `while`.