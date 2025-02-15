# Dart JSON Decoding Error Handling

This repository demonstrates a common error in Dart applications involving JSON decoding and provides a solution.

The `bug.dart` file contains code that attempts to fetch and parse JSON data from a remote API.  It fails to handle a `FormatException` that could occur if the server responds with malformed JSON.

The `bugSolution.dart` file shows the improved version, which correctly handles the `FormatException` and gracefully reports errors to the user.