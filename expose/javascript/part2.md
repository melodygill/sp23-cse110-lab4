1. At line 12, the program will print `prices.length`, which is 3.
2. At line 13, the program will print the value of `discountedPrice` from the last iteration of the for loop, which is 150.
3. At line 14, the program will print the value of `finalPrice` from the last iteration of the for loop, which is 150.
4. This function will return `[50, 100, 150]`, which is the final value of `discounted` after the for loop completes.
5. Line 12 causes an error because `i` is no longer defined once the for loop completes.
6. Line 13 causes an error because `discountedPrice` is undefined outside of the for loop.
7. Line 14 will print 150 because that is what `finalPrice` was assigned to in the last iteration of the for loop.
8. This function will return `[50, 100, 150]`, which is the final value of discounted after the for loop completes.
9. Line 11 causes an error because `i` is not defined outside of the for loop.
10. Line 12 would print 3, which is the length of `prices`. However, the code wouldn't get to line 12 because line 8 causes an error when it modifies `discounted`, which is `const`.
11. The function would error at line 8 when the code attempts to modify `discounted`, which was declared with `const`.
12. A. `student.name`  (or `student[name]`)
    
    B. `student["Grad Year"]`

    C. `student.greeting`

    D. `student["Favorite Teacher"].name`

    E. `student[courseLoad][0]`

13. A. `32` because 2 is converted to a string and then concatenated to 3.

    B. `1` because 3 is converted to int and then 2 is subtracted.
    
    C. `3` because null is converted to the integer 0.

    D. `3null` because null is converted to a string and then concatenated with 3.

    E. `4` because true is converted to the integer 1 and then added to 3.

    F. `0` because false and null are both converted to the integer 0.

    G. `3undefined` because undefined is converted to a string

    H. `NaN` because '3' is converted to the integer 3 and undefined is converted to the integer NaN, then 3 - NaN = NaN

14. A. `true` because 2 is converted to an int

    B. `false` because '2' does not come before '12' alphabetically

    C. `true` because '2' is converted to an int

    D. `false` because 2 and '2' are different types

    E. `false` because true is converted to the integer 1

    F. `true` because Boolean(2) returns true

15. The == operator will convert differently typed operands to integers and then compare them. The === operator is stricter so it will always return false if the operands are different types.
16. see part2-question16.js
17. The result will be [2,4,6]. This is because for each element `array[i]` in `array`, the function `modifyArray` adds the result of `doSomething(array[i])` to a new array and then returns the new array.
18. see part2-question18.js
19. 1
    
    4

    3
    
    2