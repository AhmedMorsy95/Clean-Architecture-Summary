# Structured Proogramming

Nowadays we are all structured programmers, though not necessarily by choice. It’s just that our
languages don’t give us the option to use undisciplined direct transfer of control.

## FUNCTIONAL DECOMPOSITION

Structured programming allows modules to be recursively decomposed into provable units, which in
turn means that modules can be functionally decomposed. That is, you can take a large-scale problem
statement and decompose it into high-level functions. Each of those functions can then be decomposed
into lower-level functions. Moreover, each of those decomposed functions can be
represented using the restricted control structures of structured programming.

## Tests

we can say that mathematics is the discipline of proving provable statements true.
Science, in contrast, is the discipline of proving provable statements false.

Rather, software is like a science. We
show correctness by failing to prove incorrectness, despite our best efforts.

Such proofs of incorrectness can be applied only to provable programs. A program that is not
provable—due to unrestrained use of goto , for example—cannot be deemed correct no matter how
many tests are applied to it.

Structured programming forces us to recursively decompose a program into a set of small provable
functions. We can then use tests to try to prove those small provable functions incorrect. If such tests
fail to prove incorrectness, then we deem the functions to be correct enough for our purposes.

## Conclusion

It is this ability to create falsifiable units of programming that makes structured programming valuable
today.This is the reason that modern languages do not typically support unrestrained goto statements.
Moreover, at the architectural level, this is why we still consider functional decomposition to be one
of our best practices.