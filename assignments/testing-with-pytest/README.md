# 📘 Assignment: Testing Python Programs with pytest

## 🎯 Objective

Learn how to use pytest to verify Python programs with automated tests. You will test normal behavior, edge cases, and expected errors so your code is easier to maintain and less likely to regress.

## 📝 Tasks

### 🛠️ Write Unit Tests for Core Functions

#### Description
Create a small module with functions that validate user data and calculate a result, then write pytest tests that check the functions behave correctly for typical and boundary inputs.

#### Requirements
Completed program should:

- Create a Python module containing at least two functions to test.
- Create a test file named `test_<module>.py`.
- Write tests for valid inputs and expected return values.
- Include tests for at least two edge cases, such as an empty value, zero, or a boundary number.
- Use clear test names that describe the behavior being checked.
- Run the tests with `pytest` and confirm that all tests pass.

### 🛠️ Test Errors and Prevent Regressions

#### Description
Extend the test suite to verify how the program handles invalid input and to protect an existing function from future changes.

#### Requirements
Completed program should:

- Update at least one function to raise a specific exception for invalid input.
- Use `pytest.raises` to test the expected exception and error type.
- Add a regression test for a bug or incorrect result that could occur after a future code change.
- Organize related tests into a test class or use pytest fixtures where they make the tests clearer.
- Include at least eight automated tests across the test suite.
- Run `pytest` successfully and submit the test output showing that all tests pass.
