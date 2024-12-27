# JavaScript Block Scope with 'let'

This code demonstrates a common misunderstanding in JavaScript regarding block scope and the `let` keyword.

Many developers coming from other languages might expect the variable `x` to be modified throughout the function. However, due to the nature of `let`, each `x` declaration creates a new variable with its own scope.

The `bug.js` file contains code showing this behavior. The `bugSolution.js` file isn't necessary because the original code doesn't contain a bug; it merely illustrates a key concept in JavaScript's scope management.