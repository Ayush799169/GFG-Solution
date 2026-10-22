## 01. Next Prime Number

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/next-prime-number/1)

### Problem Description

**Task:** Given an integer n. Write a program to find the first prime number greater than n.

#### Examples

##### Example 1

- **Input:**
```text
n = 15
```
- **Output:**
```text
17
```
- **Explanation:** 17 is next prime number.

##### Example 2

- **Input:**
```text
n = 7
```
- **Output:**
```text
11
```
- **Explanation:** 11 is the prime number next to 7.

#### Constraints

- **1.** `1 <= n <= 500`

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(n^2)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-10-22 07:58:37
- **Status:** Correct
- **Marks:** 4

```cpp
int nextPrime(int n) {
int x =n+1;
while(true){
    bool prime = x >=2;
    for (int i =2;i*i<=x;i++){
        if(x%i==0){
            prime=false;
            break;
        }
    }
    if(prime)return x;
    x++;
}
}
```

*Generated on: 10/22/2026, 7:59:06 AM*