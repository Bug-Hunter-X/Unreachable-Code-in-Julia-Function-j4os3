# Unreachable Code in Julia Function

This repository demonstrates an example of unreachable code in a Julia function.  The `println` statement and the final `return 0` statement within `my_function` will never be executed because the function already returns a value in both branches of the `if` statement.  This can lead to unexpected behavior or confusion, especially in more complex functions.

The solution demonstrates how to remove the unreachable code for improved clarity and efficiency.