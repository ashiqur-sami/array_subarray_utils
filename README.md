# Array Subarray Utils

A Python library to compute subarray sums efficiently.

## Features
- **Maximum Subarray Sum**: Finds the largest sum of a contiguous subarray.
- **Minimum Subarray Sum**: Finds the smallest sum of a contiguous subarray.
- **Maximum Circular Subarray Sum**: Handles circular arrays for the largest sum.
- **Minimum Circular Subarray Sum**: Handles circular arrays for the smallest sum.

## Installation
```bash
pip install array-subarray-utils
```
## Usage
Here is how you can use this project:

### Python Code Example
```python
from array_subarray_utils import SubarrayUtils

arr = [5, -3, 5]

# Maximum subarray sum
print(SubarrayUtils.max_subarray_sum(arr))  # Output: 10

# Minimum subarray sum
print(SubarrayUtils.min_subarray_sum(arr))  # Output: -3

# Maximum circular subarray sum
print(SubarrayUtils.max_circular_subarray_sum(arr))  # Output: 12

# Minimum circular subarray sum
print(SubarrayUtils.min_circular_subarray_sum(arr))  # Output: -3
```
