## 01. Sum of Odd and Even

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/sum-of-odd-and-even-elements3033/1)

### Problem Description

**Task:** Given an integer n, Return an array containing the sum of odd numbers and even numbers from 1 to n, where the first number is the sum of odd numbers and the second number is the sum of even numbers.Examples:Input: n = 5

#### Examples

##### Example 1

- **Output:**
```text
9 6
```
- **Explanation:** Odd numbers upto 5 are 1, 3, 5 and their sum = 1 + 3 + 5 = 9.Even numbers upto 5 are 2 and 4 and their sum = 2 + 4 = 6.

##### Example 2

- **Input:**
```text
n = 6
```
- **Output:**
```text
9 12
```
- **Explanation:** Odd numbers upto 6 are 1, 3, 5 and their sum = 1 + 3 + 5 = 9.Even numbers upto 5 are 2 , 4 and 6 and their sum = 2 + 4 + 6 = 12.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-10-19 11:33:44
- **Status:** Correct
- **Marks:** 1

```cpp
class Solution {
  public:
    vector<int> findSum(int n) {
        int oddSum=0; int evenSum =0;
        for(int i=1; i<=n;i++){
            if(i%2==0){
                evenSum=evenSum+i;
            }
            else{
                oddSum=oddSum+i;
            }
     
        }
        return{oddSum,evenSum};
    }
};
```

*Generated on: 10/19/2026, 11:34:49 AM*