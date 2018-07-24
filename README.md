# code-sample2

RPN for test using mocha.
Devise a function that, given a string containing an expression in Reverse Polish notation, evaluates that expression, returning the result. Reverse Polish notation is a mathematical notation in which every operator follows all of its operands. There is no notion of operator precedence. Instead, the expression is evaluated left to right. Some examples follow:
2 1 + => 3

5 5 + 3 * => 10 3 * => 30

You are only expected to handle well-formed strings (integers and operators separated by one space), and support integer addition and multiplication.

=========== Test cases:

"5 2 + 3 *" => 21

"5 2 * 2 * 4 +" => 24

"5" => 5

"0 1 *" => 0

============= Test ============

npm install mocha

node test.js
