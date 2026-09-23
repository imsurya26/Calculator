# Multiplication Project

This is a simple Python project that provides a basic function for multiplying two numbers.

## Files

- `multiplication.py`: Contains the `multiply(a, b)` function.
- `test_multiplication.py`: Contains unit tests for the `multiply` function using the `unittest` framework.

## Usage

You can import the `multiply` function from `multiplication.py` into your own Python scripts.

```python
from multiplication import multiply

result = multiply(4, 5)
print(f"4 * 5 = {result}")
```

## Running Tests

To verify that the multiplication function works correctly, you can run the test suite using Python's built-in `unittest` module.

Run the following command in the root directory of the project:

```bash
python -m unittest test_multiplication.py
```

This will run all the unit tests and output the results to the console.
