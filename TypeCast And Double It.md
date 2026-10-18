## 01. TypeCast And Double It

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/typecast-and-double-it--153103/1)

### Problem Description

**Task:** Given an input num as a string. You need to typecast into an integer and double it.

#### Examples

##### Example 1

- **Input:**
```text
num = "5"
```
- **Output:**
```text
10
```
- **Explanation:** Typecast "5" to int and then double it 5 * 2 = 10

##### Example 2

- **Input:**
```text
num = "12"
```
- **Output:**
```text
24
```
- **Explanation:** Typecast "12" to int and then double it 12 * 2 = 24

#### Constraints

- **1.** `0 <= num <= 10⁵`

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-10-18 11:28:27
- **Status:** Correct
- **Marks:** 1

```cpp
#include <iostream>
#include <string>
using namespace std;

int main() {
    string num;
    getline(cin, num);
    int n =stoi(num);
    cout<< n*2;
    return 0;
}
```

*Generated on: 10/18/2026, 11:28:57 AM*