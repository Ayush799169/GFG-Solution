## 01. Sizes of Data Types

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/return-size--141631/1)

### Problem Description

**Task:** Given a some variables in C or C++ code you need to store the size of these variables into a, b, c integer variables. Note: You just need to store the size into a, b, c variables only.Examples:Input: None

#### Examples

##### Example 1

- **Output:**
```text
4 8 1Explanation: printing the size of int, double, char datatype variables.
```

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-10-24 08:15:03
- **Status:** Correct
- **Marks:** 2

```cpp
#include <iostream>
using namespace std;

int main() {
    int x = 2;
    double y = 3.5;
    char z = 'g';
    
    int a=sizeof(x);
      int b=sizeof(y);
      int c=sizeof(z);

    cout << a << " " << b << " " << c << endl;
    return 0;
}
```

*Generated on: 10/24/2026, 8:15:44 AM*