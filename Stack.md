Practice Questions - 

1. **[CBSE 2024 - 3 Marks]**  
Consider a list named `Nums` which contains random integers.  
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

---

2. **[CBSE 2025 : Compartment - 3 Marks]**
A stack named **KeyStack** contains records of some computer keyboards. Each record is represented as a list containing **Make, Keys, Connectivity**. The **Make** and **Connectivity** are strings, and **Keys** is an integer. For example, a record in the stack may be `('Hitech', 105, 'USB')`.  
Write the following user-defined functions in Python to perform the specified operations on **KeyStack** :  
- (i) **push_key(KeyStack, new_key):** This function takes the stack **KeyStack** and a new record **new_key** as arguments and pushes this new record onto the stack.
- (ii) **pop_key(KeyStack):** This function pops the topmost record from the stack and returns it. If the stack is already empty, the function should display the message “Underflow”.
- (iii) **isEmpty(KeyStack):** This function checks whether the stack is empty. If the stack is empty, the function should return True, otherwise the function should return False.

---

3. **[CBSE 2025 : Compartment - 3 Marks]**  
Write the following user-defined functions in Python :
- (i) **push_vowels(S,St):** Here S is a string and St is a list representing a stack. The function should push all the vowels of the string S onto the stack St. For example, if the string S is **"Easy Concepts"**, then the function `push_vowels()` should push the elements `'E','a','o','e'` onto the stack.
- (ii) **pop_one(St):** The function should pop an element from the stack St, and return this element. If the stack is empty, then the function should display the message **‘Stack Underflow’**, and return None.
- (iii) **display_all(St):** The function should display all the elements of the stack **St**, without deleting them. If the stack is empty, the function should display the message ‘Empty Stack’.

---

4. **[CBSE 2026 - 3 Marks]**  
- A stack named **FruitStack**, implemented using list, contains records of some fruits. Each record is represented as a dictionary with keys **‘Name’, ‘Origin’, ‘Price’, and ‘Expiry’**. A sample record is given here :  
`{'Name':'Apple','Origin':'France','Price':120, 'Expiry':'12-08-2025'}`  
Write the following user-defined functions in Python to perform the specified operations on **FruitStack** :  
- (i) **push_fruit(FruitStack, Fruit):** This function takes the stack FruitStack and a new record Fruit as arguments and pushes the record stored in Fruit onto FruitStack if the Price is less than 100.
- (ii) **pop_fruit(FruitStack):** This function pops the topmost record from the stack and returns it. If the stack is already empty, the function should display **“UNDERFLOW”**.
- (iii) **display(FruitStack):** This function displays all the elements of the stack starting from the topmost element. If the stack is empty, the function should display **‘EMPTY STACK’**.






