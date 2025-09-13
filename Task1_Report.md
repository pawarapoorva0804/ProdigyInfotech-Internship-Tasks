Task 1: Test Cases for Calculator
We had developed and executed several test cases in order to test as well as invalid situations for a calculator program.

Valid Input Situations:
1. Addition of two positive numbers
• Type 5 + 3 and press = → The calculator should print 8.
2. Subtraction with the larger number
• Type 10 - 4 and press = → The calculator should print 6.
3. Multiplication with decimals
• Enter Type 2.5 * 4 and press = → The calculator should show 10.0.
4. Multiplication of two negatives
• Enter -6 * -2 and press = → The calculator should show 12.
5. Test of BODMAS Rule
• Enter 2 + 3 * 4 and press = → The calculator should respect operator precedence and show 14, not 20.

Invalid Input Situations
6. Division by zero
• Type 9 / 0 and press = → The calculator will display an error such as "Cannot divide by zero."
7. Non-numeric input
• Type 5 + A → The calculator will reject it and display "Invalid Input."
8. Very large numbers
• Type 999999999 + 1 → The calculator will display 1000000000 or display an "Overflow Error" if the number is greater than the capacity of the calculator.
9. Empty input
• Press = no input → The calculator must output 0 or print "Invalid Input".

10. Two operators pressed consecutively
• Press 5 ++ 3 → The calculator must not interpret this and print "Invalid Input" instead.