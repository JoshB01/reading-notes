# Class 8

## Expressions

Any valid unit of code that resolves to a value. Conceptually there are two types of expressions: with side effects, and those that evaluate and resolve to a value.

#### eg

"The expression x = 7 is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to seven."

"The code 3 + 4 is an example of the second expression type. This expression uses the + operator to add three and four together without assigning the result, seven, to a variable."

### Primary Expressions

'This' keyword is used to the calling object in a method. Use 'this' with dot or bracket notation:

- this['propertyName']
- this.propertyName

## Loops

Offer a quick and easy way to do something repeatedly. Many kinds of loops but are all relatively similar in the fact that they repeat and action a certain number of times.

Statements for loops in JS are:

- for statement: repeats until a specified condition evaluates to false
- do... while statement: repeats until a specified condition evaluates to false
- while statement: executes its statements as long as a specified condition evaluates to true
- labeled statement: provides a statement with an identifier that lets you refer to it elsewhere in your program
- break statement: tatement to terminate a loop, switch, or in conjunction with a labeled statement
- contimue statement: statement can be used to restart a while, do-while, for, or label statement
- for... in statement: statement iterates a specified variable over all the enumerable properties of an object. For each distinct property, JavaScript executes the specified statements
- for... of statement: statement creates a loop Iterating over iterable objects (including Array, Map, Set, arguments object and so on), invoking a custom iteration hook with statements to be executed for the value of each distinct property