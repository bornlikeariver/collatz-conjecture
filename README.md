# The Collatz Conjecture
The simplest impossible math problem (aka 3x+1)
## How it works
The Collatz Conjecture, or 3x+1, is a math problem that contains **two rules**:
1. Every even number is **divided by 2** *(i.e. **10/2 = 5, 4/2 = 2**)*
2. Every odd number is **multiplied by 3, then add 1** *(i.e. 3\*9+1 = 28)*

As long as these two rules are applied, you can insert any number and there will be absolutely no end
* If positive, the number will always jump into a **4, 2, 1** loop
* If negative, the number will jump into one of 3 loops
  - -2, 1, 4, 2, 1 (4, 2, 1, loop)
  - -5, -14, -7, -20, -10, loop
  - -17, 50, -25, -74, -37, -110, -55, -164, -82, -41, -122, -61, -91, -272, -136, -68, 34, loop

This file will stop when it reaches 1 because since it's an odd number, therefore following the 3x+1 rule. *(3\*1+1 = 4, 4/2 = 2, 2/2 = 1; 4, 2, 1 loop)*

## Important
This file can only handle positive numbers.
I warn you to not use a negative number or any symbol at all in the prompt, just stick with the simple 1234567890 digits. Otherwise, it uses a great portion of your processor and/or eventually crashes the page/browser.
Besides that, do whatever you want, make it as long as you want, just have fun.

# Instructions
- Download the file and load it into your web browser.
- Insert any positive number and it is 99.9% guaranteed to have the 4, 2, 1 loop at the end. It stops when it reaches 1 to avoid overflow.
    - This is because when it reaches 1, it follows the rule of the odd number (3x+1), therefore making it 4 again, and then 2, and then back to 1.
**Refresh to retry**
