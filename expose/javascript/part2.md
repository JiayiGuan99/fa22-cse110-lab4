1. Line 12 will print "3", because it prints the value of i after the for loop, since var is function scope and the for loop looped for 3 times and i = 2 increment by 1 at the third time, so it is 3.
2. Line 13 will print "150", because at the third time of the for loop, discountedPrice = prices[2] * (1 - discount) = 300 * (1 - 0.5) = 150 and var is function scope.
3. Line 14 will print "150", because for i = 2, finalPrice = prices[2] * 0.5 * 100 / 100 = 150 and var is function scope.
4. It will return [50, 100, 150]. Because in the for loop we push the finalPrice which is half of the original prices to discounted in this case.
5. The code causes an error because let is block scope, and line 12 is outside the block i is defined, so i is not defined here which will cause an error.
