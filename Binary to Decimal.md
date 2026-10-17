## 01. Binary to Decimal

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/binary-number-to-decimal-number3525/1)

### Problem Description

**Task:** Given a string b representing a binary number, return its decimal equivalent as an integer.

#### Examples

##### Example 1

- **Input:**
```text
b = 111
```
- **Output:**
```text
7
```
- **Explanation:** The decimal equivalent of the binary number 111 is 22 + 21 + 20 = 7.

##### Example 2

- **Input:**
```text
b = 1010
```
- **Output:**
```text
10
```
- **Explanation:** The decimal equivalent of the binary number 1010 is 2³ + 2¹ = 10.

##### Example 3

- **Input:**
```text
b = 100001
```
- **Output:**
```text
33
```
- **Explanation:** The decimal equivalent of the binary number 100001 is 2⁵ + 2⁰ = 33.

#### Constraints

- **1.** `1 <= number of bits in binary number <= 16`

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(log n)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-10-17 08:04:32
- **Status:** Correct
- **Marks:** 1

```cpp
class Solution {
  public:
    int binaryToDecimal(string& b) {
        int ans =0;
        for(int i=0; i<b.size();i++){
            ans =ans*2+(b[i]-'0');
        }
        return ans;
    }
};
```

*Generated on: 10/17/2026, 8:05:06 AM*