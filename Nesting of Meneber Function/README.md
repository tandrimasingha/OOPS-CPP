
# Object-Oriented programming Recap

- Stroustrup initially named C++ language as C with classes because C++ language was almost the same as C language but they added a new concept of classes in it.
- Classes are the extension of structures in C language.
- Structures had limitations such as; members are public and no methods.
- Classes have some additional futures than structures such as; classes that can have methods and properties.
- Classes have a feature to make class members as public and private.
- In C++ objects can be declared along with class deceleration as shown in Code Snippet 1.

# Nesting of Member Functions

If one member function is called inside the other member function of the same class it is called nesting of a member function. As shown in Code Snippet 2, we created 
a binary class that has, “s” string variable and “chk_bin” void function as private class members; and “read” void function, “ones_compliment” void function, and 
“display” void function as public class members. As shown in Code Snippet 2, we created a binary class that has, “s” string variable and “chk_bin” void function as 
private class members; and “read” void function, “ones_compliment” void function, and “display” void function as public class members. 

In the body of the “ones_compliment” function; the “chk_bin” function is called, and as we have discussed above that if one member function is called inside the other member function of the same class it is called 
 nesting of a member function. 
 
 The main thing to note here is that the function ”chk_bin” is the private access modifier of the class so we cannot access it directly by using the object, it can be only accessed inside the class or by the member function of the class.
