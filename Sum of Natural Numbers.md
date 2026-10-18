## 01. Sum of Natural Numbers

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/reverse-coding2452/1)

### Problem Description

**Task:** Given an integer n, compute the sum of all natural numbers from 1 to n (inclusive). If n is 0, the sum should be 0.Examples:Input: n = 6

#### Examples

##### Example 1

- **Output:**
```text
0
```
- **Explanation:** Since n is 0, the sum is 0.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (2)

#### Solution 1 (C++)

- **Submitted:** 2026-10-18 11:54:53
- **Status:** Correct
- **Marks:** 0

```cpp
#include <iostream>
using namespace std;

int main() {
    int n ;
    cin >> n;
cout<<n*(n+1)/2;

    return 0;
}
```

#### Solution 2 (C++)

- **Submitted:** 2026-10-18 11:45:20
- **Status:** Correct
- **Marks:** 1

```cpp
#include <iostream>
using namespace std;

int main() {
    int n ,sum=0 ,i;
    cin >> n;
    for (i=1;i<=n;i++){
    sum=sum+i;
}
    cout<< sum;

    return 0;
}
```

*Generated on: 10/18/2026, 11:55:22 AM*