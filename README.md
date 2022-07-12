# About the project
The goal of this project is to make an expert system for propositional calculus.

Your program must accept one parameter, which is the input file. It will contain a list
of rules, then a list of initial facts, then a list of queries. For each of these queries, the program
must, given the facts and rules given, tell if the query is true, false, or undetermined.

Here’s a list of the features we would like your engine to support.
+ "AND" conditions. For example, "If A and B and [...] then X"
+ "OR" conditions. For example, "If C or D then Z"
+ "XOR" conditions. For example, "If A xor E then V". Remember that this
means "exclusive OR". It is only true if one and only one of the operands is true.
+ Negation. For example, "If A and not B then Y"
+ Multiple rules can have the same fact as a conclusion
+ "AND" in conclusions. For example, "If A then B and C"
+ Parentheses in expressions. Interpreted in much the same way as an arithmetic
expression.

![](https://github.com/burjuly/expert_system/blob/main/tests/example.png)
