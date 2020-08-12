## Operators and Loops

# Comparision Operators: Evaluating Conditions

Their are tons of different symbols that are used to compare values in a script. They go as follows, *== Equal To* which compares two things to check if they are the same or not, *!= Not Equal* to which check to see if the to obects aren't identical, *=== Strict Equal To* which checks if the two values are both the same data type and values are the same. *!== Strict Not equal To* which checks to see if both data type and the values are different. *> Greater Than* which checks if the left variable is bigger than the right one, and *< Less Than* is the opposite of greater than in which the operation check if the left value is smaller than the right value. *>= Greater Than Or Equal To* this operation check if the value on the left is equal to or greater than the value on the right. *<= Less Than Or Equal To* this operation check if the value on the left is less than or equal to the value on the right. Operators normally are set up like this (number1 >= number2) wiht 1 value on one side with another value on the other with a comparison symbol in between them. At the basic level most comparison operators output a single true or false value to say wheither the statement is or is not true. Now you can also use comparison operators when comparing multiple things like (number1 + number2) > (number3 + number 4) which takes the result of the paraenthesis and then compares them to decide wheither the statement is true or false.

## Logical Operators

Logical operators allow you to compare the results of more than just one logical operator. Their is 3 of them that can help do it. *&& Logical And* Which tests if both of the conditions are true, meaning if just one of them returns false its automatically false. *|| Logical Or* which returns true if one or more of the expressions are true however if they are both false then it returns false. *! Logical Not* this wacky operator takes a single boolean value and inverts it, making the expression true if it was false or false if it was true.

## Loops

Loops check a condition if it returns true a code block will run, then the condition is check again and if it still returns true the code block will run again, it repeats until the condition given is false. Their are 3 different types of loops, *For* which runs code until a certain amount of specified time, *While* Which checks if a condition which can be something like a counter will cause the loop to run until the conditions are true. *Do While* this loops is similar to the while loop it has one key difference, it will always run the statements inside of the curly braces at least once even if the condition is false. 

## Loop Counters

Loop Counters are used as a condition, this instructs the code to run a certain amount of times. The parts of a loop is as follows the *initialization*, the *condition*, and the *update*. a normal loop looks like this

For( var i = 0; i < 10; i++) {
    document.write(i);
}

the first section thats var i = 0; is the initialization which creates a variable and sets it to 0 but only the first time the loop runs, the i < 10; section is the condition which determines how long it should continue for, and the i++ is the update which increases the counters total by 1 each time the loop is completed