1. This prints 3 because "i" stores the value of prices.length, which is 3, and since its a "var" variable type we can access it outside of the for loop in which it was declared.
2. This prints 150 because var was last set to prices[2]*(1-discount) = 300\*.5 = 150, and it's a "var" variable type so we can access it outside of the for loop in which it was declared.
3. This prints 150 because the last time finalPrice was set to something, it was set to Math.round(150 * 100) / 100 which returns 150.
4. The function returns the list [50, 100, 150] because we simply grow the returned list by the discounted value at each step.
5. This errors because "i" is accessed outside of the scope in which it was declared.
6. This errors because discountedPrice is accessed outside of the scope in which it was declared.
7. This prints 150 because the last time finalPrice was set to something, it was set to Math.round(150 * 100) / 100 which returns 150. This variable is in scope.
8. The function returns the list [50, 100, 150] because we simply grow the returned list by the discounted value at each step.
9. This errors because "i" is accessed outside of the scope in which it was declared.
10. This prints 3 because length was set to 3 in scope, the size of the prices list.
11. The function returns the list [50, 100, 150] because we simply grow the returned list by the discounted value at each step.
12. The following notations are:
    A. student.name  
    B. student['Grad Year']  
    C. student.greeting()  
    D. student['Favorite Teacher'].name  
    E. student.courseLoad[0]  
13. The results are: 
    A. '32' since 2 gets converted to a string and appended (presence of string => + means concetanation)  
    B. 1 since 3 gets converted to a number and subtraction happens  
    C. 3 since null gets converted to 0 before the addition  
    D. '3null' since null gets converted to a string before the concatenation  
    E. 4 since true gets converted to 1 before addition  
    F. 0 since false and null get converted to 0 before addition  
    G. '3undefined' since undefined gets converted to a string before concatenation  
    H. NaN since undefined gets converted to NaN before the subtraction and any operation with a NaN results in a Nan  
14. The results are:  
    A. true since '2' gets converted to a number before comparison  
    B. false since we compare strings by alphanumical order  
    C. true since '2' gets converted to a number before comparison  
    D. false since we are checking for strict equality without any conversion  
    E. false since true gets converted to 1 before comparison  
    F. true because Boolean(2) gets converted to true  
15. == can perform conversions before checking for equality but === is a strict equality check that doesn't convert values, checking for both type and value equality
17. The output will be [2, 4, 6]. This is because for each element in the original array, doSomething doubles the value and adds it to a new array that is returned by modifyArray
19. The output of the above code is 1 4 3 2