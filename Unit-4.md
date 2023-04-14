Function:
    A block of organized, reusable code that is used to perform a single, related action.
    Gives high degree of code reusing.
    Standard Library Functions:
        Built-in functions 
    User Defined Functions:
        Created by the user based on its own requirements.
    
Defining a function:
    Begins with "def" keyword followed by the function name and parentheses "()".
    Input parameters or arguments should be pplaced inside the parentheses.
    The code block within a function starts with a colon ":" and is indented.
    The statement "return #expression"exits a function.

Function Parameters:
    Values passed into the function.
    Used to manipulate the function for desired output.

Variable Scope:
    The location where we can find a variable and also access it if required is called the scope of the variable.
    Global Variables:
        Defined and declared outside any function.
        Can be used by any part of the code.
        They are variables throughout the program life time.
    Local Variables:
        Declared inside the function.
        Can only be accessed inside the function.

Return Statement:
    Used to:
        End the execution of the function call.
        Return the result.
    The statements after the return statement are not executed.
    If the return statement is without any expression, the the special value "None" is returned.

Required Argument:
    Passed to a function in correct positional order.
    Number of arguments in function call should match exactly with function definition.

Keyword Argument:
    The caller identifies the arguments by the parameter name.
    This allows to skip arguments or place them out of order because the Python interpreter is able ti use the keywords provided to match the values with parameters.

Default Argument:
    Default values indicate that the function argument will take that value if no argument value is passed during the function call.
    Assigned by using the assignment operator (=) of the form keywordname = value.

Variable Length Argument:
    Used when we don't know how many arguments we will be using in the function.
    "*"  is used before the parameter name.

Lambda Function or Anonymous Function:
    Means that the function is without a name.
    The "lambda" keyword is used to define an anonymous function.
    Syntax:
        lambda arguments : expression
    Any number of arguments but only one expression
    Lambda function can be used wherever function objects are required.

Docstrings:
    Python Documentation Strings (or docstrings) provide a convenient way of associating documentation with Python modules, functions, classes and methods.
    Syntax:
        function_name.__doc__

Recursive Functions:
    A defined function can call itself multiple times.

Modules:
    Allows to reuse one or more function in the program even in those programs where function definitions is not defined.

Import Modules:
    Maths Module:
        sqrt(x) -> Returns the square root of x
        ceil(x) -> Returns the smallest integer greater than or equal to x
        floor(x) -> Returns the largest integer less than or equal to x
        factorial(x) -> Returns the factorial of x.
        exp(x) -> Returns e raised to power x
        pi -> Returns the value of mathematical constant pi which is equal to 3.141592......
        