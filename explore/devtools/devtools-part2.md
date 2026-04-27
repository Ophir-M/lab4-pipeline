# DevTools Part 2

What was the bug?
The bug was that num1 and num2 were strings because they were retrieved using .value from input fields. As a result, JavaScript concatenated them instead of performing numerical addition.

How would you fix it?
Convert the inputs to numbers before adding them, for example using Number(num1) and Number(num2).
