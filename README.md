# Python Programs Collection

Three beginner Python programs: **Factorial**, **Fibonacci series** and **Structure-to-Dictionary conversion**.

## Programs

### 1. `factorial.py`
Calculates `n!` two ways:
- **Iterative** — multiplies `1 × 2 × … × n` in a loop.
- **Recursive** — uses `n! = n × (n−1)!` with `0! = 1! = 1` as the base case.

Negative input raises a `ValueError` with a clear message.

```
Enter a non-negative integer: 5
5! (iterative) = 120
5! (recursive) = 120
```

### 2. `fibonacci.py`
- `fibonacci_series(n)` returns the first `n` terms: `0, 1, 1, 2, 3, 5, …`
- `nth_fibonacci(n)` returns a single term (0-indexed).

Each new term is the sum of the previous two (`a, b = b, a + b`).

```
How many Fibonacci terms? 7
Series: [0, 1, 1, 2, 3, 5, 8]
```

### 3. `structure_to_dict.py`
Converts structured data into Python dictionaries:
| Input | Method | Example output |
|---|---|---|
| `@dataclass` object | `dataclasses.asdict()` | `{'roll_no': 'S001', 'name': 'Aarav', ...}` |
| Normal class object | `vars(obj)` | `{'title': 'Clean Code', ...}` |
| List of `(key, value)` tuples | `dict(pairs)` | `{'python': 3, 'java': 2}` |
| List of student records | dict comprehension | `{'S001': {...}, 'S002': {...}}` |

## How to run
Requires Python 3.10+.
```bash
python factorial.py
python fibonacci.py
python structure_to_dict.py
```
