Download Link: https://assignmentchef.com/product/solved-stack-is-a-data-structure-where-data-is-accessed
<br>
A stack is a data structure where data is accessed using the LIFO (last in first out) principle. In this problem, use a stack to check whether a string has balanced parentheses (, ) and brackets {, }, [, ], or not.

A string that has balanced parentheses and brackets will be said to be balanced. Any character that is not one of (, ), [, ], {, or } is not important when deciding if a string is balanced and can be ignored.

We will define balanced as follows. A string str is balanced

<ul>

 <li>if str does not contain a parenthesis or bracket symbol, or</li>

 <li>str consists of a balanced string surrounded by opening and closing parentheses or matching brackets. That is, str is (b), {b} or [b], where b is any balanced string, or</li>

 <li>if str is the concatenation of any two balanced strings. That is, str is bc, where b and c are any balanced strings.</li>

</ul>

You will complete the provided Balanced class that has two static methods isBalanced(String) and numberOfBalancedStrings(String[]).

Your isBalanced method must use the java.util.Stack class (in a way that solves the problem) to receive any grades for this problem.

http://docs.oracle.com/javase/8/docs/api/java/util/Stack.html

Examples

The following strings have balanced parentheses

<ul>

 <li>(), ()()</li>

 <li>cat, c(at), (hello)(kitty)</li>

 <li>if( ((x-y) &lt; 4) || (x &gt; 12))</li>

 <li>()(((s)))()()()()(x()((y))(x))()(ccccc(w))ssss()</li>

</ul>

The following strings do not have balances parentheses

<ul>

 <li>), )(a), )a(</li>

</ul>

The following strings have balanced parentheses and brackets

<ul>

 <li class="ng-binding">a, [], {}, [()], []{}({}),</li>

 <li>for(int i=0; i&lt;12; i+=1){x[i]+=f(1);}</li>

</ul>

The following strings do not have balanced parentheses and brackets

<ul>

 <li>(], {), [}, [}, (], ({)}h, [(]())</li>

 <li>for(int i=0; i&lt;12; i+=1){</li>

</ul>

Note: You will receive partial marks if you code only works for parentheses (and not brackets).