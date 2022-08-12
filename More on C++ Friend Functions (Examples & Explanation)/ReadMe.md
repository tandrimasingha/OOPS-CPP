# Friend Functions in C++
As we have already discussed in previous lectures friend functions are those functions that can access the private data members of the other class.

## Code Snippet 1: Friend Function Example 1
As shown in a code snippet 1,

- 1st class “Y” is declared at the top which is known as forward declaration to let the compiler know that this class is defined somewhere in the program.
- 2nd class “X” is defined which consists of private data member “data” and public member function “setValue” which assigns the value to the private data member “data”. At the end friend function “add” is declared.
- 3rd class “Y” is defined which consists of private data member “num” and public member function “setValue” which assigns the value to the private data member “num”. At the end friend function “add” is declared.
- 4th function “add” is defined which add the value of the objects of class “X” and “Y” and print it.

## Code Snippet 2: Main Program

As shown in Code Snippet 2,

- 1st object “a1” of the data type “X” is declared
- 2nd function “setValue” is called by the object “a1” and the value “3” is passed
- 3rd object “b1” of the data type “Y” is declared
- 4th function “setValue” is called by the object “b1” and the value “15” is passed
- 5th function “add” is called and the objects “a1” and “b1” are passed to it. The function “add” will add the values of both objects and print them.
