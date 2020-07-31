What is a Comparison Operator? 

A comparison operator evaluates conditions :

They are Eight Comparison Operators: 
equal to ==  (3=='3') true
strick equal to ===  (3==='3') false. One is a number the other a string. Strick equal is the industry standard, so you don't get bugs in your code. 
not equal != ('hello' != 'goodbye') true  
strick not equal !== (3 !== 3) false Strick  not equal is also the industry standard. Use it rather then != when possible
greater than > (4<3) false 
less than < (4<3) true 
greater than or equal to >= (4>3) true 
less than or equal to <= (3<=3) true 

Logical operators allow you to compare two or more statements. They are three logical operators: 

Logical and (&&) both expressions need to be true to evaluate as true. 
((2<5) && (3>=1)) true 

Logical or (||) if either expression is true, the expression is true. 
Only if both expressions are false will evaluate as false. 
((2<5) || (2<1)) true  

Logical not (!) take a single boolean value and inverts it. If it was false without the logical not, it is now true and vice versa.  
!(2<1) true

Logical expressions read from left to right. If the first condition provides enough information, then the second is not evaluated. 

ex) false && anything. 
The expression had found a false condition and cannot both be true. The second condition isn't evaluated.

ex) true || anything  
The expression had found a true condition, and only one has to be true. The second condition isn't evaluated.  

What is a loop? 

A loop checks a condition. If it is true, the code will run. The code is rechecked, and if it still returns true, it will continue to run until it is false.  

They are three types of loops for, while and do-while. 

A for loop is used when a programmer needs the loop to run a specific amount of times. It is the most common loop used. The condition is a counter that tells the loop how many times it should run.

If a programmer doesn't know how many times a loop should run, then a while loop should be used. The condition isn't a counter and will run as long as the condition. Be careful! If the condition is always true, you can get caught in an infinite loop and break your code. 

A do-while loop is precisely like a while loop, except it will always run the statement inside it curly brackets at least once even if it is false. 


