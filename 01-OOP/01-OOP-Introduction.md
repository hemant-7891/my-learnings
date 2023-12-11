# Introduction to Object oriented programming
## Agenda
- [Introduction to Object oriented programming](#introduction-to-object-oriented-programming)
  - [Agenda](#agenda)
  - [Key terms](#key-terms)
    - [Abstraction](#abstraction)
    - [Encapsulation](#encapsulation)
    - [Classes](#classes)
    - [Object](#object)

### Object-oriented programming
> Object-oriented programming (OOP) is a programming paradigm that uses objects to model real-world things and aims to implement state and behavior using objects.

### Abstraction
> Abstraction is the process of hiding the implementation details of a program from the user.

### Encapsulation
> Encapsulation is used to hide the values or state of a structured data object inside a class, preventing direct access to them by clients in a way that could expose hidden implementation details or violate state invariance maintained by the methods.

### Classes
> A class is a blueprint which you use to create objects.

### Object
> An object is an instance of a class.

## Abstraction

> the creation of abstract concept-objects by mirroring common features or attributes of various non-abstract objects or systems of study[3] – the result of the process of abstraction.
> is a mechanism which represent the essential features without including implementation details

Objects in an OOP language provide an abstraction that hides the internal implementation details. Similar to the coffee machine in your kitchen, you just need to know which methods of the object are available to call and which input parameters are needed to trigger a specific operation. But you don’t need to understand how this method is implemented and which kinds of actions it has to perform to create the expected result.

Advantages of Abstraction:

* Abstraction is used to create a boundary between the application and the client code. This could help us to reduce the design and implementation complexity of software.
* In complex software, abstraction helps us separate responsibilities into software entities (classes, method, etc.) that only know the required functionality of each other but not how that functionality is implemented.
* Abstraction maximizes ease of use for the relevant information. In other words, the code with proper abstraction help programmers to quickly make sense of what that code does and what it is meant to be used for. It avoids code duplication and increases code reusability.
* Abstraction allows the programmer to simplify programming and shift focus from implementation details of actions toward the classes, available methods, etc. It will enable the user to avoid writing low-level code.
* It allows the programmer to change the internal implementation of methods or concrete classes without hampering the interface.
* Using abstraction, we can increase the code security as only relevant details will be provided to users.


## Encapsulation

> encapsulation refers to the bundling of data with the methods that operate on that data, or the restricting of direct access to some of an object's components. Encapsulation is used to hide the values or state of a structured data object inside a class, preventing direct access to them by clients in a way that could expose hidden implementation details or violate state invariance maintained by the methods

Encapsulation may also refer to a mechanism of restricting the direct access to some components of an object, such that users cannot access state values for all of the variables of a particular object. Encapsulation can be used to hide both data members and data functions or methods associated with an instantiated class or object.

Advantages of Encapsulation:
* `Hiding Data` - Users will have no idea how classes are being implemented or stored. All that users will know is that values are being passed and initialized.
* `More Flexibility` - Enables you to set variables as read or write-only. Examples include: setName(), setAge() or to set variables as write-only then you only need to omit the get methods like getName(), getAge() etc.
* `Easy to Reuse` - With encapsulation it's easy to change and adapt to new requirements.