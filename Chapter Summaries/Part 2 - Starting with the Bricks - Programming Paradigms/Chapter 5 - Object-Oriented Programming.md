# Chapter 5 - Object-Oriented Programming

- Although all of the following existed before OOP, OOP made them safer and easier:
  - **Encapsulation**
  - **Inheritance**
  - **Polymorphism**
- Previous implementations of polymorphism required pointers to functions which was dangerous. OOP makes this trivial, which is why we can say _OOP imposes discipline on indirect transfer of control._
- Polymorphism allows us to implement a kind of "plugin" architecture where different implementations of the same interface can easily be switched out.
- **Dependency Inversion:** Imagine you have a High-Level class 1 (HL1) which depends on a Mid-Level class (ML1). In this instance HL1 depends on ML1. However we can create an interface which defines the contract the ML1 is going to fulfil. HL1 now depends on the interface, and ML1 implements this interface. This means that ML1 can be switched out for other implementations which also implement the interface. Dependency inversion can be implemented through dependency injection where ML1 (or another implementation of the interface) would be passed into HL1.
- **Advantages of Dependency Inversion:** If you create the "plugin" architecture dependency inversion allows you can deploy these plugins separately from the modules that use them. It lets you control the direction of dependencies in your code.