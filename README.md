Tiger is a tiny compiler. 
The main function is translate the Java language to C language and implements a garbage collector which based on the classical Chemny's copy algorithm. 
In the front-end, it uses ll(k) and recursive descent algorithm to tokenize and parse the abstract syntax tree.
In the back-end, it uses several optimization such as Dead-Code elimination, Algebraic reduction, Variable liveness analysis, Static Single Assignment based on Three Address Code and what's more we also have the constant propagation. In a word, tiger is a toy-level interpreter.