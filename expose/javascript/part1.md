# Part 1

1. `values added: 20`  
No error.

2. `final result: 20`  
No error.

3. You should not use `var` because it is function-scoped, not block-scoped, meaning variables declared inside blocks are still accessible outside those blocks. This can cause unexpected behavior and bugs.

4. `values added: 20`  
No error.

5. ReferenceError: `result is not defined`  
Because `let` is block-scoped, so `result` is not accessible outside the `if` block.

6. TypeError: Assignment to constant variable  
Because `const result = 0` cannot be reassigned.

7. Nothing is printed because the function crashes before line 13. The error happens when trying to reassign a `const` variable.
