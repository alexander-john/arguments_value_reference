# arguments_value_reference
This program demonstrates the concept of arguments passed by value and by reference.

It may be useful to access an external variable from within a function. To do that 
arguments can be passed by reference, instead of by value.

To gain access to its arguments, the function declares its parameters as references. 
In C++, references are indicated with an ampersand (&) following the parameter type.

When a variable is passed by reference, what is passed is no longer a copy, but the variable
itself, the variable identified by the function parameter, becomes somehow associated with
the argument passed to the function, and any modification on their corresponding local variables
within the function are reflected in the variables passed as arguments in the call.

If instead the parameters were defined without ampersand signs, the variables would not be passed 
by reference, but by value, creating instead copies of their values.

## What You Need
* Clion

## Steps To Build & Run
1. Download Zip
2. Unzip
3. Open main.cpp with CLion
4. Done!