# PRODIGY_ST_01
Test Case 1: Addition of Two Positive Integers

Test Case ID: TC_ADD_001

Test Description: Validate that the calculator correctly adds two positive integers.

Preconditions: Calculator is loaded and ready for input.

Test Steps:

1. Enter 8.


2. Press +.


3. Enter 5.


4. Press =.



Expected Result: Display shows 13.



---

✅ Test Case 2: Subtraction with a Negative Result

Test Case ID: TC_SUB_002

Test Description: Validate subtraction when the result is negative.

Preconditions: Calculator is functional.

Test Steps:

1. Enter 3.


2. Press -.


3. Enter 10.


4. Press =.



Expected Result: Display shows -7.



---

✅ Test Case 3: Multiplication with Decimals

Test Case ID: TC_MUL_003

Test Description: Validate multiplication involving decimal numbers.

Preconditions: Calculator accepts decimal input.

Test Steps:

1. Enter 2.5.


2. Press ×.


3. Enter 4.2.


4. Press =.



Expected Result: Display shows 10.5.



---

✅ Test Case 4: Division Resulting in Decimal

Test Case ID: TC_DIV_004

Test Description: Validate division that results in a non-integer value.

Preconditions: Calculator supports decimal output.

Test Steps:

1. Enter 7.


2. Press ÷.


3. Enter 2.


4. Press =.



Expected Result: Display shows 3.5.



---

✅ Test Case 5: BODMAS Rule Evaluation

Test Case ID: TC_BODMAS_001

Test Description: Validate calculation respects BODMAS rule.

Preconditions: Calculator supports expressions with parentheses.

Test Steps:

1. Enter (2 + 3) × 4.


2. Press =.



Expected Result: Display shows 20.



---

✅ Test Case 6: Operation with Negative Numbers

Test Case ID: TC_NEG_001

Test Description: Validate multiplication of two negative numbers.

Preconditions: Calculator supports negative input.

Test Steps:

1. Enter -3.


2. Press ×.


3. Enter -5.


4. Press =.



Expected Result: Display shows 15.



---

❌ Test Case 7: Division by Zero

Test Case ID: TC_ERR_001

Test Description: Validate error handling for division by zero.

Preconditions: Calculator should handle math errors.

Test Steps:

1. Enter 9.


2. Press ÷.


3. Enter 0.


4. Press =.



Expected Result: Display shows error message: "Cannot divide by zero" or similar.



---

❌ Test Case 8: Non-Numeric Character Input

Test Case ID: TC_ERR_002

Test Description: Validate that calculator rejects non-numeric input.

Preconditions: Calculator is in standard mode.

Test Steps:

1. Try to enter A.



Expected Result: Input is rejected or an error message is shown: "Invalid input".



---

❌ Test Case 9: Empty Input on Evaluation

Test Case ID: TC_ERR_003

Test Description: Validate handling when equal is pressed without input.

Preconditions: Calculator is empty.

Test Steps:

1. Press = without entering any input.



Expected Result: Display remains 0 or shows "Enter an expression".



---

✅ Test Case 10: Complex Expression with All Operators

Test Case ID: TC_COMPLEX_001

Test Description: Validate evaluation of a complex expression using multiple operations.

Preconditions: Calculator supports BODMAS and full expression parsing.

Test Steps:

1. Enter 5 + 2 × (3 - 1).


2. Press =.



Expected Result: Display shows 9.
