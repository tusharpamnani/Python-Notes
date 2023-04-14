Conditional Branching Statement:
    jumps from one part of the code to another part of the code depending on whether a particular condition is satisfied or not.
    Allows to execute a statement selectively based on certain conditions.

Selection Control Structure:
    if
    if else
    nested if
    if elif else 

If statement:
    if condition:
       statement1
    statement2
    
    if condition is true, both statement1 and statement2 will be executed
    if condition is false, only statement2 will be executed while skipping the if block

If-Else statement:
    if condition:
        statement1
    else:
        statement2
    if the condition is true, only statement1 will be executed.
    if the condition is false, only statement2 will be executed.

Nested if:
    if condition1:
        statement1
        if condition2:
            statement2
    To perform more complex check (more then one condition is to be checked), nested if is used.
    if the condition1 is true, statement1 will be executed and then if the condition2 will be true, statement2 will be executed
If elif Else:
    if condition1:
        statement1
    elif condition2:
        statement2
    else:
        statement3

Basic Loop:
    Iterative statement are decision control statements taht will be used to repeat the execution of a list of statements
        While loop:
            It provides the mechanism to repeat one or more statements while a particular condition is true.
                while (condition):
                    statement
        For loop:
            aka Definite loop as you know the exact bumber of times you want the loop to execute.
                for i in range():
                    statement
            range(start:end:step):
                Built-in function used to iterate over a sequence of numbers.

Break Statement:
    Used to terminate the execution of the nearest loop in which it appears.

Continue Statement:
    Forces to execute the next iteration of the loop while skipping the rest of thecode inside the loop for the current iteration only.

Pass Statement:
    Used as a placeholder for the further code.
    When executed, nothing happens but you avoid getting an error when empty code is not allowed.
    Empty code is not allowed in:
        Loops
        Function Definition
        Class Definition
        If Statements

Else Statement with Loops:
    The else block after for/while is executed only when the loop is not terminated by a break statement.