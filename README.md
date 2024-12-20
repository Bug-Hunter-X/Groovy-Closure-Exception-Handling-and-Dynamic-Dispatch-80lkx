# Groovy Closure Issues
This repository demonstrates two uncommon issues related to closures in Groovy:

1. **Exception Handling:** Exceptions thrown inside a closure may not be clearly indicated unless specifically handled within the closure itself.
2. **Dynamic Dispatch:** Closures interacting with dynamic dispatch (method overriding) can exhibit unexpected behavior.

The `bug.groovy` file shows examples of these issues. The `bugSolution.groovy` file provides solutions to handle them.