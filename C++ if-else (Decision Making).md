## 01. C++ if-else (Decision Making)

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/c-if-else-decision-making4138/1)

### Problem Description

**Task:** Given an integer n. Your task is to check if the integer is greater than, less than or equal to 5.If the integer is greater than 5, then print "Greater than 5" (without quotes).If the integer is less than 5, then print "Less than 5".If the integer is equal to 5, then print "Equal to 5".Note:- Do not print the next line after the result.Examples :Input: n = 8

#### Examples

##### Example 1

- **Output:**
```text
Less than 5Explanation: 4 is less than 5
```

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (2)

#### Solution 1 (C++)

- **Submitted:** 2026-10-18 11:26:51
- **Status:** Correct
- **Marks:** 0

```cpp
class Solution {
  public:
    string compareFive(int n) {
        if(n>5)
        {
            return" Greater than 5";
        }
        
      else if (n<5){
        return"Less than 5";    
        }
        
        else{
            return"Equal to 5";
        }
        
    }
};
```

#### Solution 2 (C++)

- **Submitted:** 2026-10-18 11:24:08
- **Status:** Correct
- **Marks:** 1

```cpp
class Solution {
  public:
    string compareFive(int n) {
        if(n>5)
        {
            return" Greater than 5";
        }
        
      else if (n<5){
        return"Less than 5";    
        }
        
        else{
            return"Equal to 5";
        }
        
    }
};
```

*Generated on: 10/18/2026, 11:27:08 AM*