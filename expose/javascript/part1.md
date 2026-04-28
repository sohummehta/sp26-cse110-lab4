## Part 1 Answers

1. values added: 20
2. final result: 20
3. Because it has function scope instead of block scope, which is something let and const have. This can lead to naming conflicts and possibly me accessing a variable I didn't expect to be able to access in the scope
4. values added: 20
5. There will be an error for this line because the let is block scoped within the if block, so result doesn't exist at line 13 technically
6. I believe it will be an error because since we assigned result as a const, it can't be reassigned in line 7
7. Same thing as above, so I don't think line 13 will be reached