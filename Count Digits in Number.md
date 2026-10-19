## 01. Count Digits in Number

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/count-total-digits-in-a-number/1)

### Problem Description

**Task:** Given a number n, return the count of digits in this number.Examples :Input: n = 1567

#### Examples

##### Example 1

- **Output:**
```text
5
```
- **Explanation:** The number of digits in 99999 is 5.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(log n)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-10-19 11:43:10
- **Status:** Correct
- **Marks:** 2

```cpp
class Solution {
  public:
    int countDigits(int n) {
        
        if(n==0)
        return 1;
        return (int)log10(n)+1;
    }
};
```

*Generated on: 10/19/2026, 11:43:41 AM*