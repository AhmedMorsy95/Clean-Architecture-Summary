# Paradigm Overview
There are 3 paradigms and it's unlikely for others to exist.
## Structured Programming

Dijkstra showed that the use of unrestrained jumps
(goto statements) is harmful to program structure.
It's better to use if/else statements.

"Structured programming imposes discipline on direct transfer of control"

## Object Oriented Programming

The function became a constructor for a class, the local
variables became instance variables, and the nested functions became methods. This led inevitably to
the discovery of polymorphism through the disciplined use of function pointers

"Object-oriented programming imposes discipline on indirect transfer of control"

## Functional Programming

Based on immutability concept.

A functional language has no assignment statement. Most functional languages do, in fact, have some means to alter
the value of a variable, but only under very strict discipline.

"Functional programming imposes discipline upon assignment"

## Thoughts

The three paradigms together remove goto statements, function pointers, and assignment. Is there
anything left to take away?

## Conclusion
We use polymorphism as the mechanism to cross architectural boundaries; we use functional programming to impose discipline on the location of and access to data; and we use structured programming as the
algorithmic foundation of our modules.

Notice how well those three align with the three big concerns of architecture: function, separation of
components, and data management.