1. In line 9, the code will print the expected result of (10 + 10) = 20 because var was correctly declared within the scope.

2. This line on the other hand will not run correctly, most likely causing an error because var was only declared within the if conditional and the javascript file will not recognize any variable called result.

3. Therefore, we should generally tend to avoid, and I heard that var is not longer good Javascript practice because of the amount of errors and difficulties it may cause for coders. Coders must constantly track variables within their code base, causing many errors to inevitably happen.

4. We can expect that line 9 using the let keyword will print the expected result (10 + 10) = 20 as let was correctly declared within the scope.

5. This will likely result in an error because let is also declared within the if conditional and will not recognize the variable result outside of the if statement.

6. Const keyword is inside the block scope, allowing the code to print the expected result of (10 + 10) = 20.

7. This will cause an error because we notice that like the other two variables, const is a block scope and not able to be seen outside the conditional.


