# Dart Reduce() Method Error with Empty List

This repository demonstrates a common error encountered when using the `reduce()` method in Dart with an empty list.  The `reduce()` method requires at least one element to perform the reduction operation; attempting to use it on an empty list results in an error.

The `bug.dart` file shows the incorrect implementation, which throws an exception. The `bugSolution.dart` file provides a corrected version that handles the empty list scenario gracefully.

## Solution
The solution involves checking if the list is empty before calling `reduce()`. If the list is empty, a default value (e.g., 0 for summing) is returned, preventing the error.