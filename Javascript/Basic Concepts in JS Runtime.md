## Synatx Parser

Synatx parser is a program which goes through javascript file/code and checks for grammatical errors.
The Syntax parser is part of JS Compiler.

## Lexical Environment

The place/syntax where the code(function/var) in scope.
There can be many lexical environment. Areas of code(function body).


## Execution Context

Execution context refers to the part of the Lexical Context which is currently being executed(running). 

## Hoisting

The javascript compilation process is a two step proccess. First is parsing of code, In this stage the compiler goes
through javascript code and keeps track of every identifier and its type which it encounters.

The javascript engine set up memory space for these identifiers in a *Scope Object*. The variables are assigned undefined, as place holder till it reaches the assignment in execution stage.   