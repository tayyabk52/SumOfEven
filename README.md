**README.md**

# Sum of Even Numbers

## Problem Statement
Write a program that takes an integer `n` as input and calculates the sum of all even numbers from `1` to `n` inclusive.

### Example
- **Input**: `n = 10`
- **Output**: `Sum = 30` (2 + 4 + 6 + 8 + 10)

### Instructions
- Implement your solution in `main.cpp`.
- Make sure to compile and test your code locally before pushing your changes.

## Submission
- Once you have completed the program, commit and push your code to this repository.

## Testing
- Your code will be tested automatically using the provided input files. Ensure that your output matches the expected output format.

---

**main.cpp**

```cpp
#include <iostream>

int main() {
    int n;
    std::cout << "Enter a number: ";
    std::cin >> n;

    int sum = 0;
    for (int i = 1; i <= n; i++) {
        if (i % 2 == 0) {
            sum += i;
        }
    }

    std::cout << "Sum = " << sum << std::endl;
    return 0;
}
