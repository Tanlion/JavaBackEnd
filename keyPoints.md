# Core Java
## Java Concepts

### Package Levels
package level: all other classes in the same package can visit this class
"Access Modifiers:" <br />
**public:** visible in the same package as well as the outside packages. <br />
**private:** Only those Classes who have defined these variables and methods can visit. It is the import way to realize Encapsulation. <br />
**protected:**  Besides the Classes who have defined these variables and methods, protected classes can also be visited by thire subclass. <br />
**default:** JAVA 8. The default access modifier is also called package-private, which means that all members are visible within the same package but arenot accessible from other packages.


### Types for Inner classes
Inner class or nested class is a class declared entirely within the body of another class or interface. Types of nested classes in Java are:

**static class**: the keyword static indicates that the particular member belongs to a type itself, rather than to an instance of that type. This means that only one instance of that static member is created which is shared across all instances of the class.

**local class**: They are declared in the body of a function. They can only be referred to in the rest of the function. They can use local variables and parameters of the function, but only one that are declared "final". Can be very helpful for creation a class with generic type fields, where the type variables are defined in the method.

**anonymous class:** Anonymous classes enable you to make your code more concise. They enable you to declare and instantiate a class at the same time. They are like local classes except that they do not have a name. Use them if you need to use a local class only once.

**member class:** They are declared outside a function (hence a "member") and not declared "static".

JVM: Java Virtual Machine is a process virtual machine that can execute Java bytecode.
