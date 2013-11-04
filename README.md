# Wraith

[![Coverage Status](https://coveralls.io/repos/Akvelog/Wraith/badge.png?branch=master)](https://coveralls.io/r/Akvelog/Wraith?branch=master) 

Wraith is a simple parser combinator library (not monadic nor memoized) inspired
by Boost.Spirit. It is not complete as Spirit but the fundamental operators are
implemented.

## Features

* Basic operators - epsilon and failure for building high-level operators.
* Lexical operators - token operator based on Perl regex.
* Basic combinators - alternative, sequence and kleene star operators.
* Semantic action support.
* Combinators as overloaded perl operators - BNF-like usage.

## TODO

* Profile.
* Non-greedy many for better performance.

## Further work

* First-class object parsing.
