## 01. Decision Making

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/decision-making/1)

### Problem Description

**Task:** Given two integers, n and m. The task is to check the relation between n and m. Print "less" if n < m, "equal" if n = = m, and "greater" if n > m.

#### Examples

##### Example 1

- **Input:**
```text
n = 4, m = 8
```
- **Output:**
```text
less
```
- **Explanation:** 4 < 8 so print 'less'.

##### Example 2

- **Input:**
```text
n = 8, m = 8
```
- **Output:**
```text
equal
```
- **Explanation:** 8 = 8 so print 'equal'.

##### Example 3

- **Input:**
```text
n = 8, m = 4
```
- **Output:**
```text
greater
```
- **Explanation:** 8 > 4 so print 'greater'.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-10-17 06:41:56
- **Status:** Correct
- **Marks:** 1

```cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    int n, m;
    cin >> n >> m;
 if(n<m){
     cout<<"less ";
 }
 else if (n==m){
     cout<<"equal";
 }else{

     cout<<"greater";
 }
    
    return 0;
}
```

*Generated on: 10/17/2026, 6:42:33 AM*