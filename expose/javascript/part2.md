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
12. A. student.name
    B. student["Grad Year"]
    C. student.greeting()
    D. student["Favorite Teacher"].name
    E. student.courseLoad[0]
13. A. 32 since integers map to their exact string representation
    B. 1 since string map to the integer representation
    C. 3 since null maps to 0 
    D. 3null since objects map to the string representation
    E. 4 since true maps to 1
    F. 0 since false and null maps to 0
    G. 3undefined since object map to the string representation
    H. NAN since `undefined` will convert to `NAN`
14. A. true since string '2' becomes a number 2
    B. false sicne 2 is bigger than 1
    C. true since string '2' becomes a number 2
    D. false since 2 and '2' has different type
    E. false since true is 1 
    F. true since Boolean(2) is true
15. `==` would check equality with type conversion while `===` would check equality without type conversion.
17. 