# Lua Nil Arithmetic Bug

This repository demonstrates a subtle bug related to how Lua handles `nil` values in arithmetic operations.  When `nil` is involved in addition, the result is `nil`, which might not be the expected behavior for all developers.

The `bug.lua` file shows the unexpected result.  The `bugSolution.lua` provides one way to handle this case defensively.

This example highlights the importance of explicit nil checks in Lua code to prevent unexpected behavior and improve code robustness.