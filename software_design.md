# Software Design Methodologies

1. 
- Cohesion - describes how well the functions or classes within the program relate to each other and work together to perform a single task.
- Coupling - describes the links between different sections of the program and how much dependency there is on other parts of the code.

Good structured design has high cohesion and low coupling.

2. 
Top down looks at the system as a whole and identifies systems which can then be broken down into sub-systems until the smallest level is reached. This approach is better when specifications are unkown and the system has to be made from scratch.
Bottom up looks at the smallest components of the system and creates systems/classes to encapsulate them until a hierarchy is formed, which is useful when the details of the system are known.
Function oriented design is bottom-up, because the individual functions are coded first which are the smaller building blocks of the whole program.


3. 
A class diagram would be most useful in OOD because it shows how the classes connect with each other and represent inheritance, abstract classes and interfaces.


4. 
- **Encapsulation** - defines the way in which code is kept in the classes it belongs to in an organised way. A class will contain the properties and methods it needs, keeping it separate from the rest of the unrelated classes.
- **Abstraction** - hides details of how the code runs from the user, which is achieved by creating classes with methods which describe real objects.
- **Inheritance** - when a subclass inherits the properties and methods of a more general superclass.
- **Polymorphism** - describes components as appearing in many forms, for example, it enables multiple methods to be created with the same name and a similar purpose but each with a way to process different inputs.



5.
OOD incorporates abstract classes and interfaces to make the code more flexible.
FOD can involve higher order functions in which other functions can be passed through as parameters.

6.
I would use OOD because you can create generic superclasses to cover the general transactions and payment details and methods - and then create specific subclasses later for specific items. This is because in OOD, the program can be extended without having to modify the core classes that run the system and then these extended classes can be customisable to the specific purpose of the program.














