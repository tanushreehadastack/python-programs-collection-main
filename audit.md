# README Claims Audit

| Claim in README | True? | Evidence |
|---|---|---|
| `factorial.py` computes n! iteratively and recursively | Yes | `factorial_iterative` and `factorial_recursive`; input 10 → 3628800 for both |
| Negative input raises a clear error | Yes | Both functions raise `ValueError("Factorial is not defined for negative numbers.")` |
| `fibonacci.py` returns the first n terms starting 0, 1 | Yes | Input 5 → `[0, 1, 1, 2, 3]` |
| `nth_fibonacci` is 0-indexed | Yes | `nth_fibonacci(4)` → 3 |
| `structure_to_dict.py` converts dataclass, object, tuple list and records | Yes | Running the file prints all four dictionaries |
| Requires Python 3.10+ | Yes | Uses `list[int]` type hints |
