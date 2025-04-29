1. In line 12, since the variable var i was declared in the for loop, this means that i will still be seen and correctly return 3, the length of the prices array.

2. In line 13, similar to the answer in 1, since the variable discountedPrice was declared within the for loop, it can still be assecible outside the loop and will result (300 *0.5) = 150.

3. In line 14, finalPrice will successfully return 150 as the var was declared within the function.

4. The function will return the expected discounted array [50, 100, 150].

5. In line 12, We will get an error because using let is block scoped meaning although we used a for loop, we cannot access it outside the block.

6. In line 13, using let will similarly cause the same problem and result in an error because of the way the let keyword was built.

7. Since let was declared within the function, this let keyword will work properly calculating finalPrice as (30000/100) = 300.

8. This function will return [50, 100, 150]. Discounted will have no errors to look out for.

9. This will cause an error because the let keyword is blocked scoped and console.log(i) is outside of the block that let was declared in.

10. Length was declared within the function, allowing it to successfully return the value 4.


11. This return will return discounted correctly because const is declared within the function. After calculting the values based on the arguements in line 17, we get the final return value to be: [50, 100, 150].

12. 
Notations:
A. student.name
B. student.GradYear
C. student.greeting()
D. student.FavoriteTeacher.name
E. student.courseLoad[0]


13. 
Arithmetic:
A. '32'
B. 1
C. 3
D. '3null'
E. 4
F. 0
G. '3undefined'
H. NaN

14. 
Comparison:
A. true
B. false
C. true
D. false
E. false
F. true

15. 
The difference between both equal operators is that "==" does not care about type before comparing and "===" compares types.

17.  The idea is that modify array is first called with the given array [1, 2, 3]. Then after each iteration of the array, the doSomething function will be called, multiplying the numbers in the array by 2, returning the results of the callback will be directly changed within the modifyArray.

19. The console log will print 1 4 3, then pause and finally return 2.