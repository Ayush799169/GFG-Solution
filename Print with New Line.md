## 01. Print with New Line

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/the-new-line/1)

### Problem Description

**Task:** There is a string "Geeks for Geeks", print each word on a separate line.

> **Note:** No input required for this problem.

#### Examples

##### Example 1

- **Input:**
```text
Not Required
```
- **Output:**
```text
Geeks for Geeks
```
- **Explanation:** Each word is printed on a separate line.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-10-17 07:58:51
- **Status:** Correct
- **Marks:** 1

```cpp
#include <iostream>
using namespace std;

int main() {

string s="Geeks for Geeks";
stringstream ss(s);
string word;
while(ss>>word){
    cout<<word<<endl;
}

    return 0;
}
```

*Generated on: 10/17/2026, 7:59:21 AM*