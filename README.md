# Expression-trees

// In the project you need to code one class that extends the abstract class ExpressionTree.  
// Your class needs to code one constructor and one output method as well as any helper methods
// that you find useful.
// The goal is to process mathematical expressions that are provided as strings.

// In the main program that tests your class,
// the Utility getInput method reads a mathematical expression that is typed as input.
// The expression can contain any combination of numbers, variable identifiers and mathematical operations.
// These mathematical operations are +, -, *, /, ( and )

// The constructor should turn an input expression into the content of a binary (expression) tree.
// The tree can then be printed in prefix, postfix, or fully parenthesised infix notation.
// The first two of these methods have been coded for you in the abstract class ExpressionTree, you need to code the third.

// For example the expression   5 + (x / y + z * 7) - 2  would be printed as
//                              - + 5 + / x y * z 7 2  in prefix order
//  or                          5 x y / z 7 * + + 2 -  in postfix order
//  or               (( 5 + ((x / y) + (z * 7))) - 2)  in fully parenthesised infix notation.
