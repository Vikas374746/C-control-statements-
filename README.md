### **Experiment 6: If-Else Statements in C++**

**Title of the Experiment:**
To study and implement decision-making using if-else and nested if statements in C++

---

**Objective / Aim:**
To learn how to use if-else and nested if-else constructs in C++ for different decision-making scenarios such as:

1. Finding the greatest of three numbers
2. Checking if an alphabet is a vowel or consonant
3. Determining if a number is even, odd, or zero

---

**Tools Used:**

* Code::Blocks IDE or Visual Studio Code
* GCC Compiler (MinGW or g++)
* Operating System: Windows or Linux

---

### **Theory:**

The `if-else` statement in C++ is a fundamental decision-making construct.
It allows the program to choose one path out of two or more based on conditions.

Types of if-else constructs:

* Simple if
* if-else
* else-if ladder
* Nested if-else

These are commonly used for comparing values, validating input, and applying logic.

---

### **Programs Covered:**

1. **Greatest of Three Numbers:**

   * Takes three numbers as input
   * Uses nested if-else to compare them
   * Outputs the greatest value or equality status

2. **Vowel or Consonant Check:**

   * Accepts a character input
   * Uses if-else to check if the character is a vowel
   * Validates whether the input is a lowercase alphabet

3. **Even, Odd, or Zero Check:**

   * Takes a number from the user
   * Checks whether the number is zero, even, or odd using modulus and equality checks

---

Here are the **algorithms** for all three `if-else` based programs you mentioned — written clearly and step-by-step so you can **copy and paste** them directly into your record file:

---

### **1. Algorithm to Find the Greatest of Three Numbers**

**Aim:** To find the greatest among three numbers using nested if-else.

**Algorithm:**

1. Start
2. Declare three variables: `num1`, `num2`, `num3`
3. Read values of `num1`, `num2`, and `num3` from the user
4. Check if `num1 > num2`

   * If true, check if `num1 > num3`

     * If true, display `num1` as the greatest
     * Else, display `num3` as the greatest
   * Else, check if `num2 > num3`

     * If true, display `num2` as the greatest
     * Else, display `num3` as the greatest
5. If none of the above, all numbers are equal — display that
6. Stop

---

### **2. Algorithm to Check Vowel or Consonant**

**Aim:** To determine whether a given lowercase character is a vowel or a consonant.

**Algorithm:**

1. Start
2. Declare a character variable `ch`
3. Read the character from the user
4. Check if the character lies between `'a'` and `'z'`

   * If true, check if `ch` is `'a'`, `'e'`, `'i'`, `'o'`, or `'u'`

     * If true, display that `ch` is a vowel
     * Else, display that `ch` is a consonant
   * Else, display "Invalid input"
5. Stop

---

### **3. Algorithm to Check Even, Odd, or Zero**

**Aim:** To check whether a number is even, odd, or zero using if-else-if.

**Algorithm:**

1. Start
2. Declare an integer variable `num`
3. Read the value of `num` from the user
4. If `num == 0`

   * Display "Number is zero"
5. Else if `num % 2 != 0`

   * Display "Number is odd"
6. Else

   * Display "Number is even"
7. Stop

---


### **Flowchart (Text Description):**

Start → Input → Condition check with if-else → Display result → End

---

### **Conclusion:**

The if-else and nested if-else constructs were successfully used in multiple decision-making scenarios.
This experiment helped in understanding conditional logic and flow control in C++.


