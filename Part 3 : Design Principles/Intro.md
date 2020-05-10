# Design Principles

The SOLID principles tell us how to arrange our functions and data structures into classes, and how
those classes should be interconnected. The use of the word “class” does not imply that these
principles are applicable only to object-oriented software. A class is simply a coupled grouping of
functions and data. Every software system has such groupings, whether they are called classes or not.
The SOLID principles apply to those groupings.

The goal of the principles is the creation of mid-level software structures that:

• Tolerate change,

• Are easy to understand, and

• Are the basis of components that can be used in many software systems.

Here is what **SOLID** stands for

• SRP: The Single Responsibility Principle
An active corollary to Conway’s law: The best structure for a software system is heavily influenced
by the social structure of the organization that uses it so that each software module has one, and only
one, reason to change.

• OCP: The Open-Closed Principle
Bertrand Meyer made this principle famous in the 1980s. The gist is that for software systems to be
easy to change, they must be designed to allow the behavior of those systems to be changed by
adding new code, rather than changing existing code.

• LSP: The Liskov Substitution Principle
Barbara Liskov’s famous definition of subtypes, from 1988. In short, this principle says that to build
software systems from interchangeable parts, those parts must adhere to a contract that allows those
parts to be substituted one for another.

• ISP: The Interface Segregation Principle
This principle advises software designers to avoid depending on things that they don’t use.

• DIP: The Dependency Inversion Principle
The code that implements high-level policy should not depend on the code that implements low-
level details. Rather, details should depend on policies.
