# Mathematical Review: Base 10

## Overview
  * The human hand has ten digits, which are also known as fingers.
  * There are ten digits in the Base 10 numbering system.
  * We have all learned to count in Base 10.
  * As humans, we are comfortable in performing mathematical operations in base 10.
In COMP122, we will be learning about computer architecture and assembly languages. A key component in using these systems is knowing various numbering systems and data representations. For example, we will be learning about base 2, base 8, base 16, and base 64 within this class.

On a computer system, we need to perform basic mathematical operations. The operations are not performed in base 10, but in base 2. That is to say that a computer system uses binary numbers in all of its computations. Moreover, we are limited in the size of the numbers that can be used within our calculations.

In this assignment, you are to perform a number of simple mathematical operations in Base 10. The purpose of this assignment is to have you review the fundamentals of these operations and to prepare you to perform the same types of operations using binary numbers (that is to say, using Base 2 computations).

While completing this exercise, pay attention to the algorithm or process you use to solve each problem. Show all of your work in the space provided. Notice that you are limited to numbers in the range of 0 .. 9,999. Perhaps, there might be a problem or two in which you will not be able to solve given the provided <b>space</b>. When such an <b>exception</b> occurs, simply denote you were not able to solve that problem.

---
# Mathematical Review: Base 10
### Due Date: 
### Directions: See the README.md file.
---
## Name:                                <!-- answer -->
## GitHub Account:                      <!-- answer -->

### Section One
1. Addition of Whole Numbers
  1. Perform the following additions.
  1. Show your work by replacing each 'x' with the appropriate character

  * 13 + 5
   ```
     xxx0              <!-- answer -->
     xxxx              <!-- answer -->
   + xxxx              <!-- answer -->
   ------
     xxxx              <!-- answer -->
   ```

  * 13 + 8
   ```
     xxx0              <!-- answer -->
     xxxx              <!-- answer -->
   + xxxx              <!-- answer -->
   ------
     xxxx              <!-- answer -->
   ```

  * 1345 + 655
   ```
     xxx0              <!-- answer -->
     xxxx              <!-- answer -->
   + xxxx              <!-- answer -->
   ------
     xxxx              <!-- answer -->
   ```

  * 5676 + 4334
   ```
     xxx0              <!-- answer -->
     xxxx              <!-- answer -->
   + xxxx              <!-- answer -->
   ------
     xxxx              <!-- answer -->
   ```

1. Addition of Fix Point Numbers
  1. Perform the following additions.
  1. Show your work by replacing each 'x' with the appropriate character

  * 13.5 + 5.0
   ```
     xxxx.xxxx              <!-- answer -->
     xxxx.xxxx              <!-- answer -->
   + xxxx.xxxx              <!-- answer -->
   ------
     xxxx.xxxx              <!-- answer -->
   ```

  * 45.67 + 0.8
   ```
     xxxx.xxxx              <!-- answer -->
     xxxx.xxxx              <!-- answer -->
   + xxxx.xxxx              <!-- answer -->
   ------
     xxxx.xxxx              <!-- answer -->
   ```

  * 134.5 + 0.655
   ```
     xxxx.xxxx              <!-- answer -->
     xxxx.xxxx              <!-- answer -->
   + xxxx.xxxx              <!-- answer -->
   ------
     xxxx.xxxx              <!-- answer -->
   ```

  * 566.76 + 4334.0
   ```
     xxxx.xxxx              <!-- answer -->
     xxxx.xxxx              <!-- answer -->
   + xxxx.xxxx              <!-- answer -->
   ------
     xxxx.xxxx              <!-- answer -->
   ```

### Section Two
1. Did you read the overview of this assignment? 
   *                   <!-- answer -->
1. Why was this exercise assigned to you by your Professor?
   *                   <!-- answer -->
1. What is a natural number?
   *                   <!-- answer -->
1. What is a whole number? A number without fractions.
   *                   <!-- answer -->
1. What is an integer?
   *                   <!-- answer -->
1. What is a real number? 
   *                   <!-- answer -->
1. What is a complement?
   *                   <!-- answer -->
1. What is a carry?
   *                   <!-- answer -->
1. What is overflow?
   *                   <!-- answer -->
1. What is an exception?
   *                   <!-- answer -->



### Appendix:
* Example additions of 961 + 921 and 7236 + 4216 are provided as a template
* Note that it is not possible to add 7236 and 4216 together with the space provided.

#### Addition of 961 + 921 
* Template:
   ```
     xxx0  (Carry Row)
     xxxx  (Augend Row)
   + xxxx  (Addend Row)
   ------
     xxxx  (Sum Row)
   ```
* Answer:
   ```
     1000
     0961
   + 0921
   ------
     1882  
   ```

#### Addition of 7236 + 4216 
* Template:
   ```
     xxx0 (Carry Row)
     xxxx (Augend Row)
   + xxxx (Addend Row)
   ------ 
     xxxx (Sum Row)
   ```
* Answer:
   ```
     0010
     7236
   + 4216
   ------
     1452     # Note the sum is 11,452, but this
              # number overflowed the space provided.
   ```
