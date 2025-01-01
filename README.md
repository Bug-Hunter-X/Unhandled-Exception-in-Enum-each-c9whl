# Elixir Enum.each Exception Handling

This example demonstrates a common issue in Elixir where an unhandled exception within `Enum.each` prevents the rest of the enumeration from completing.  The solution shows how to handle exceptions properly to ensure all list elements are processed or the exception is handled gracefully.

The `bug.ex` file contains the code with the error, and `bugSolution.ex` provides the corrected version.