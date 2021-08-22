# Data Types

Contemporary digital computers store information using patterns of bits<sup>1</sup> (binary digits). These patterns are arbitrary, and cannot be interpreted without context.

A _data type_ is an agreement about how to interpret a particular pattern of bits. The same bit pattern may represent different things in different situations, but in order for computers to function properly, computer programs and computer programmers must agree on the context in which data (patterns of bits) are understood and exchanged.

Consider the following pattern.

```1000 0000```

Depending on the context, this pattern could be interpreted as the numbers 128, -128, the character Ç (C-cedilla) or an instruction<sup>2</sup>. It could in fact mean anything we want it to, as long as we _agree_ about that meaning. 

Data types common to different computers and programming languages are:
1. integers (... -1, 0, 1, 2 ...)
2. floating point numbers (-234.56, 1.0)
3. characters (a, A)
4. strings (Hello, world!)
5. booleans (true, false)