Practice Questions - 

1. Consider a list named Nums which contains random integers.  
Write the following user defined functions in Python and perform the specified operations on a stack named `BigNums`.  
**(i) PushBig():** It checks every number from the list `Nums` and pushes all such numbers which have **5 or more digits** into the stack, `BigNums`.  
**(ii) PopBig():** It pops the numbers from the stack, BigNums and displays them. The function should also display "Stack Empty" when there are no more numbers left in the stack.  
---
For example: If the list Nums contains the following data: `Nums = [213,10025,167,254923,14,1297653,31498,386, 92765]`  
Then on execution of `PushBig()`, the stack BigNums should store: `[10025, 254923, 1297653, 31498, 92765]`
And on execution of PopBig (), the following output should be displayed:
92765
31498
1297653
254923
10025
Stack Empty
