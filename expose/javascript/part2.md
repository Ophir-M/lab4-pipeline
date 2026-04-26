# Part 2

1. `3`  
Because `var i` is function-scoped, so after the loop finishes, `i` is still accessible outside the loop and has the value 3.

2. `150`  
Because `var discountedPrice` is function-scoped, so after the loop finishes it still exists and holds the last computed value, 300 * 0.5 = 150.

3. `150`  
Because `var finalPrice` is function-scoped, so after the loop it retains the last computed value and is accessible outside the loop.

4. `[50, 100, 150]`  
Because each price is multiplied by `1 - discount` and pushed into the array.

5. ReferenceError: `i is not defined`  
Because `let i` is block-scoped to the `for` loop, so it is not accessible outside the loop.

6. ReferenceError: `discountedPrice is not defined`  
Because `let discountedPrice` is block-scoped inside the loop and not accessible outside.

7. `150`  
Because `finalPrice` is declared outside the loop and updated each iteration, so it keeps the last value.

8. `[50, 100, 150]`  
Because each discounted value is pushed into the array and returned.

9. ReferenceError: `i is not defined`  
Because `let i` is block-scoped to the loop and not accessible outside.

10. `3`  
Because `length` is declared with `const` in the function scope and is accessible outside the loop.

11. `[50, 100, 150]`  
Because each discounted price is calculated and pushed into the array, which is then returned.

12.  
A. `student.name`  

B. `student['Grad Year']`  

C. `student.greeting()`  

D. `student['Favorite Teacher'].name`  

E. `student.courseLoad[0]`

13. Arithmetic

`'3' + 2` -> `'32'`  
String concatenation occurs because 2 is converted to a string.

`'3' - 2` -> `1`  
The string `'3'` is converted to the number 3.

`3 + null` -> `3`  
`null` is converted to 0.

`'3' + null` -> `'3null'`  
`null` is converted to a string.

`true + 3` -> `4`  
`true` is converted to 1.

`false + null` -> `0`  
`false` becomes 0 and `null` becomes 0.

`'3' + undefined` -> `'3undefined'`  
`undefined` is converted to a string.

`'3' - undefined` -> `NaN`  
`undefined` converts to `NaN`.

14. Comparison

`'2' > 1` -> `true`  
`'2'` is converted to the number 2.

`'2' < '12'` -> `false`  
Both are strings, so JavaScript compares them lexicographically.

`2 == '2'` -> `true`  
`==` allows type conversion.

`2 === '2'` -> `false`  
They have different types.

`true == 2` -> `false`  
`true` converts to 1, and 1 is not equal to 2.

`true === Boolean(2)` -> `true`  
`Boolean(2)` is `true`, and both values are booleans.

15. `==` compares values after type conversion, while `===` compares both value and type without conversion.

17. `[2, 4, 6]`  
Because each element in the array is passed into `doSomething`, which multiplies it by 2, and the results are pushed into a new array.

19. `1 4 3 2`
