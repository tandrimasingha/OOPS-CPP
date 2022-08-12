
# Member Friend Functions in C++
Friend functions are those functions that have the access to private members of the class in which they are declared. 
The main thing to note here is that only that function can access the member function which is made a friend of the other class.

# Friend Classes in C++
Friend classes are those classes that have permission to access private members of the class in which they are declared. The main thing to note here is that if the class is made friend of another class then it can access all the private members of that class. 
a complex class is declared at the top which is known as forward declaration. Forward declaration hints to the compiler that this class is declared somewhere forward in the code. After that calculator class is defined this consists of three public member functions, “add”, “sumRealComplex”, and “sumCompComplex”. The “add” function will add the values of “a” and “b” and return the value. The “sumRealComplex” and “sumCompComplex” are taking two objects of the complex class. 
