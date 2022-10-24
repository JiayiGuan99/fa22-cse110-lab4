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
