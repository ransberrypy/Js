# VARIABLES
Containers or space in memory that information is saved in and named so we can call it

### CREATING VARIABLES
Variables are created by using the let keyword, followed by the name of the variable and the data you want to save.

syntax:
> let firstname = "Jared"

Variables has some few rules
- 
- it cannot start with a number
- You cannot use a reserved key work: If you must use a reserved keyword, you can prefix it with $ or _ 
- When using Uppercase makesure you do that for only classes and not variables.

eg:

> let _function = "Apocalypto"

> let $new = "new"

<hr>

## DATA TYPES:

When we are coding to solve problems in the real world we need to represent data or information somehow to the language, lets look at some data that Js has

- Numbers : both decimals and whole numbers. In Js everything is a decimal.
- Strings : Alphabets or texts
- Boolean : True or False
- Undefined: Value taken by a variable not yet defined
- Null : empty
- BigInt : Hold large integers than Number can.

The above are all types but are <b>Primitive Types</b>


### VARIABLE DECLARATION KEY (LET, CONST, VAR)
- let : used to declare variables that will change in our code.

- const: Used to declare data that wont change.


<br>

<b>
<em>Best practice</em>: Always use const to declare variables, until you are sure it will change then we use let.
</b>

<br>

<b>Let is block scoped and var is function scoped</b>