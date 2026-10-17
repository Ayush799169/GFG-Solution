## 01. Learn to Comment

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/learn-to-comment/1)

### Problem Description

**Task:** Given three lines that print the values of a, b, and c. Comment out the line that prints the value of b.Comments are useful in any programming language to describe the purpose of functions or operations. They are ignored by the compiler, so they do not affect the execution of the code.Examples: Input: a = 5, b = 6, c = 15

#### Examples

##### Example 1

- **Explanation:** 5 15Input:a = 6, b = 8, c = 10 6 10

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (3)

#### Solution 1 (C++)

- **Submitted:** 2026-10-17 07:01:55
- **Status:** Correct
- **Marks:** 0

```cpp
#include <iostream>
using namespace std;

int main() {
    int a;
    int b;
    int c;
    cin >> a >> b >> c;

    cout << a << endl;
    
//    cout << b << endl;

    cout << c << endl;
}
```

#### Solution 2 (C++)

- **Submitted:** 2026-10-17 07:01:37
- **Status:** Correct
- **Marks:** 0

```cpp
#include <iostream>
using namespace std;

int main() {
    int a;
    int b;
    int c;
    cin >> a >> b >> c;


    cout << a << endl;
//    cout << b << endl;

    cout << c << endl;
}
```

#### Solution 3 (C++)

- **Submitted:** 2026-10-17 06:58:44
- **Status:** Correct
- **Marks:** 1

```cpp
#include <iostream>
using namespace std;

int main() {
    int a;
    int b;
    int c;
    cin >> a >> b >> c;


    cout << a << endl;
//    cout << b << endl;

    cout << c << endl;
}
```

*Generated on: 10/17/2026, 7:02:25 AM*