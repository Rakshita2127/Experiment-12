# Experiment-12
The constructor's name is the same as that of its class. Although they can be declared in the private section of the class, constructors are typically declared in the public section. Constructors lack a return type because they don't return values. When we create a class object, a constructor is automatically called. When variables must be started before an object is called, constructors are utilized.
Constructors' prototype looks like this:<class-name> (parameters list);
It is possible to define constructors both inside and outside of the class declaration. <class-name> (list-of-parameters) { // constructor definition }; is the syntax for defining the constructor inside the class.
<class-name>: :<class-name> (list-of-parameters){ // constructor definition}; is the syntax for defining the constructor outside of the class.

## Program 0
### Aim: 
Study constructors
### Software used: 
Visual Studio Code
### Theory:
When an object of a class is created in C++, a constructor—a special member function—is automatically called. Initializing the object's attributes is its main objective. Constructors lack a return type and have the same name as the class. They allow for the controlled creation of objects and the initialization of those objects using specified logic or default values.
### Output:
<img width="832" alt="image" src="https://github.com/user-attachments/assets/f067457b-3b5a-49d1-8149-adae5c82aa41">
### Conclusion:
We learned constructors in C++

## Program 1
### Aim: 
To implement Default Constructors. 
### Software used: 
Visual Studio Code
### Theory:
A constructor with all default arguments or one that accepts no parameters is called a default constructor. C++ offers a default constructor by default if no constructor is defined explicitly. For built-in types, it initializes the class's members with their default values; for other objects, it calls their default constructors.
### Output:
<img width="705" alt="image" src="https://github.com/user-attachments/assets/4e521b20-835f-45b4-9a1c-0caf3eeef2eb">

### Conclusion:
We learned how to implement default constructors in C++. 

## Program 2
### Aim: 
To implement Parameterized constructos. 
### Software used: 
Visual Studio Code
### Theory:
When creating an object, a parameterized constructor enables the passing of arguments. The user-supplied values are used by this constructor to initialize the object's attributes. By permitting various initializations depending on the passed parameters, it provides flexibility in the creation of objects.
### Output:
<img width="706" alt="image" src="https://github.com/user-attachments/assets/2cdc25b2-116a-4772-bf8e-89af14b9ca52">

### Conclusion:
We learned how to implement parameterized constructors in C++. 

## Program 3
### Aim: 
To implement Copy Constructors
### Software used: 
Visual Studio Code
### Theory:
An existing object can be copied into a new one using a copy constructor. It duplicates the attributes of the given object using a reference to an object of the same class as its parameter. When an object is explicitly copied, passed by value, or returned by value, the copy constructor is invoked. It guarantees that the copied object and the new object are in the same state.
### Output:
<img width="692" alt="image" src="https://github.com/user-attachments/assets/7bc34b54-60a9-4732-af80-374fe56c0a1e">

### Conclusion:
We learned how to implement copy constructors in C++. 

## Program 4
### Aim: 
To use Constructors with default Arguments. 
### Software used: 
Visual Studio Code
### Theory:
These constructors permit the default values of one or more parameters. The default values are used when an object is created if no arguments are supplied for these parameters. This feature combines default behavior with the flexibility of parameterized constructors.
### Output:
<img width="806" alt="image" src="https://github.com/user-attachments/assets/72c79373-b71c-4e89-8af1-9ec4bcacef95">

### Conclusion:
We learned how to use constructors with default arguments in C++. 

## Program 5
### Aim: 
To implement destructors. 
### Software used: 
Visual Studio Code
### Theory:
When an object is explicitly deleted or goes out of scope, a special member function known as a destructor is called automatically. The destructor lacks a return type and parameters, and it shares the same name as the class, with a tilde (~) coming before it. In order to ensure that objects clean up after themselves when they are no longer needed, destructors are mainly used to release resources, such as memory or file handles.
### Output:
<img width="696" alt="image" src="https://github.com/user-attachments/assets/4391a182-3aae-4689-80e4-c4cade682691">

### Conclusion:
We learned how to implement destructors in C++. 
