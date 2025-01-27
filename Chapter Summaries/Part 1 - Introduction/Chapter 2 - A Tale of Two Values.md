# Chapter 2: A Tale of Two Values

- Each software system provides two different values: behaviour and structure.
- **Behaviour:** What the system does. It is the list of requirements that provides stakeholders some value.
- **Stucture:** The structure of the system controls how easy it is to change. _"The difficulty in making such a change should be proportional only to the scope of the change, and not to the shape of the change."_ This simply means that your system architecture should be flexible enough to handle a wide variety of changes. If your system can only change in a few ways, your stakeholders are likely to request a feature which doesn't fit into that box and so causes chaos.
- You can argue that structure is in some ways even more important than behaviour:
  - _"If you give me a program that works perfectly, but is impossible to change, then it won't work when the requirements change, and I won't be able to make it work. Therefore the program will become useless."_
  - _"If you give me a program that does not work but is easy to change, the I can make it work, and keep it working as requirements change. Therefore the program will remain continually useful._
- Software architecture is **not urgent and important**. It is the software developer's job to ensure that urgent and not important things (like new features) are not prioritised over the architecture.