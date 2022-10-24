1. Line 12 will print "3", because it prints the value of i after the for loop, since var is function scope and the for loop looped for 3 times and i = 2 increment by 1 at the third time, so it is 3.
2. Line 13 will print "150", because at the third time of the for loop, discountedPrice = prices[2] * (1 - discount) = 300 * (1 - 0.5) = 150 and var is function scope.
3. Line 14 will print "150", because for i = 2, finalPrice = prices[2] * 0.5 * 100 / 100 = 150 and var is function scope.
4. It will return [50, 100, 150], because in the for loop we push the finalPrice which is half of the original prices to discounted in this case.
5. The code causes an error because let is block scope, and line 12 is outside the block i is defined, so i is not defined here which will cause an error.
6. Same as no.5, line 13 causes an error because discountedPrice is type let that is defined in another block and is not defined at line 13.
7. Line 14 will print "150", because it in the same block where finalPrice is defined, and the value is 0.5prices[2]*100/100 = 150.
8. It will return [50, 100, 150], because discounted is returned in the same block its defined, value is same as no.4.
9. It will cause an error, same reason as no.5, line 11 is outside the block i is defined and i is type let.
10. It will return "3" because its the length of prices.
11. It will return [50, 100, 150], because discounted is not being reassigned, so it is allowed to push elements into it.
12. A) student.name B) student['Grad Year'] C) student.greeting D) student.greeting() E) student.courseLoad[0]
13. A) '32' integers map to their exact string representation. B) 1, to perform subtraction, '3' is converted to integer and then - 2. C) 3, null is 0. D) '3null', null got converted to string and concatenate with '3'. E) 4, true has integer value of 1. F) 0, false and null both have integer value of 0. G) '3undefined', undefined is converted into string. H) NaN, '3' convets to integer and undefined is NaN, so the result is NaN, not a number.
14. A) true, '2' converts to integer. B) false, for string comparison, '2' > '1'. C) true, '2' converts to integer 2. D) false, since they have different data types. E) false, ture = 1. F) ture, Boolean(x) returns true or all non-zero values.
15. '==' can be used to compare different type, it will perform proper convertion to do the compare. '===' can only compare values in same data type and will return false for different data types comparision.
17. [2,4,6] will be the result. We call modifyArray with [1,2,3] and function doSomething as parameters, it will return a new array that each element is modified by doSomething, so each entries of array will * 2 in the for loop and be push into newArr in the same order which is the final result.
19. 1432. It will print 14 first, then 3 because of the setTimeout, then wait for 1 sec to print 2.
