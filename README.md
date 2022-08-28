# Part II Dissertation

I have developed the theory and implemented the type checker for a dependently typed language, PiMu.
My language aims to have a syntax close to the lambda calculus for reasons of simplicity and familiarity.
There is only a single level of syntax, which includes both types and terms.
Datatype declarations and type-level functions are both definable as regular terms, leading to a relatively simple presentation of the type theory.
It does not include some of the higher level features that exist in some other dependently typed languages, such as implicit arguments, term holes and pattern matching.
This is an intentional choice to keep the scope of the project manageable, but I have made an effort to ensure the theory and implementation are easily extendable.
Notable features of the language are indexed recursive datatypes, recursive functions, let bindings, dependent product types, sum types and explicit equality types.
These will all be explained in detail in the implementation section of this dissertation.

`diss.pdf` - The final submitted dissertation

`bool` - Example defining a boolean type in the language

`nat` - Example defining a natural numbers, including a proof of commutativity

`vector` - Example defining vectors with some utility functions such as append and zip
