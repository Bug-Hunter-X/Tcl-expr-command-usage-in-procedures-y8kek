# Tcl expr command usage in procedures
This repository demonstrates a common error in Tcl when using the `expr` command within procedures.  The example shows how to correctly handle the return value of an expression to prevent unexpected behavior.

## Bug
The `bug.tcl` file contains a procedure named `wrong_proc` that incorrectly uses the `expr` command. It attempts to directly use the result of the expression in a `return` statement without proper handling of potential issues.

## Solution
The `bugSolution.tcl` file provides a corrected version of the procedure, ensuring that the return value is handled correctly. This ensures that the procedure always returns a valid Tcl value. 
