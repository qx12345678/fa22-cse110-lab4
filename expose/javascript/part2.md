1. 3, because after `for` loop, `i` becomes 2, because the size of `prices` is 3.
2. 150, because after `for` loop, `i` becomes 2, and the discountedPrice would be `prices[2]*(1-discount)` which is 300*(1-0.5) = 150.
3. 150, because discountedPrice is 150 after `for` loop, so finalPrice would be `Math. round(150 * 100) / 100` which is 150.
4. [50,100,150], because in each loop inside `for`, `discounted` will be pushed `finalPrice`, which are 50,100,150.
5. error, `i` is decleared by `let`, which has code block.
6. error, `discountedPrice` is decleared by `let`, which has code block.
7. 150, `finalPrice` is decleared outside of `for` loop, and after loop, it is 150.
8. [50,100,150], `prices` and `discount` is given, after loop, `discounted` is [50,100,150], and return it correctly. 
9. error, `discounted`, `discountedPrice`, and `length` is decleared by `const` which can not reassign.
10. 3, because `length` would not be changed, and length of `prices` is 3.
11. [50,100,150], `discounted` is constant, but the value inside array could be changed.