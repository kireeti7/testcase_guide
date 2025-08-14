# testcase_guide

1. A test case in manual testing usually includes:
2. Test Case ID – Unique name/number.
3. Test Scenario / Title – Short description of what’s tested.
4. Preconditions – What needs to be true before the test.
5. Test Steps – Step-by-step instructions to execute.
6. Expected Result – What should happen.
7. Actual Result – What actually happened (filled after execution).
8. Status – Pass/Fail.



1. Test Cases for Drop Down Field

Think about:

UI & functionality

Data validation

Default values

Error handling

Example areas to test:

Is the drop-down visible on the page?

Does it open on click/tap?

Are all expected options present?

Are options sorted logically (alphabetical, by category, etc.)?

Can you select one option at a time?

Does the default option match the requirements?

Does it work on all browsers/devices?

Does it behave correctly when there are many options (scrolling)?

What happens if you leave it unselected (if it’s mandatory)?

2. Test Cases for Text Field

Focus on:

UI appearance

Length limits

Input validation

Special characters

Example areas to test:

Is the text field present with correct label?

Can you type text into it?

Is the max character limit enforced?

Does it accept allowed characters only? (e.g., numbers only for phone)

Does it reject HTML/script injection (security)?

Does placeholder text appear as expected?

Does validation error appear for invalid input?

Does it retain entered data after page refresh (if required)?

3. Test Cases for Gmail Registration & Sign-in

Here, you test workflow, validation, and security.

Registration:

All mandatory fields present?

Proper error messages for missing/invalid data?

Strong password rules enforced?

Email uniqueness check working?

CAPTCHA validation working?

Account activation link sent to correct email?

Activation link expires after certain time?

Sign-in:

Valid credentials allow login?

Invalid credentials give correct error?

Account lock after multiple failed attempts?

“Forgot Password” link works?

Remember Me function works?

Session expires after inactivity?

4. Test Cases for Website Testing

Broad category — think:

Functional: Links, forms, search, navigation.

UI: Layout, colors, responsiveness.

Compatibility: Browsers, devices.

Performance: Load speed.

Security: HTTPS, no broken auth.

Example:

All links lead to correct pages.

No broken images.

Site loads within required time.

Works on mobile view without layout break.

HTTPS certificate valid.

5. Test Cases for Checkbox Field

Is checkbox visible with correct label?

Can it be selected/deselected?

Can multiple checkboxes be selected at once (if allowed)?

Is “Select All” checkbox working?

State saved after form submit?

Error shown if mandatory checkbox not selected?

Keyboard accessibility (Tab + Space) works?

6. Test Cases for CAPTCHA Functionality

Focus: Bot prevention & Usability.

CAPTCHA appears when required?

User can read/solve it easily?

Wrong CAPTCHA shows error?

New CAPTCHA loads on refresh?

Accessible for visually impaired (audio CAPTCHA)?

Works on all browsers?

Backend verifies correctly?

7. Test Cases for Date of Birth Field

Correct date format (dd/mm/yyyy or mm/dd/yyyy)?

Calendar opens when clicking the field?

User can select date manually or via calendar?

Cannot select a future date?

Minimum age restriction enforced?

Leap year dates handled?

Error shown for invalid dates?

8. Test Cases for Credit Card/Debit Card Functionality

Card number field accepts only numbers?

Correct length enforced (16 digits)?

Luhn algorithm validation for card number?

Expiry date format correct and not expired?

CVV length validated?

Error messages for invalid entries?

Secure transmission (HTTPS)?

Successful transaction when details correct?

9. Test Cases for Pen Functionality (I’m assuming this is for a hardware pen or stylus in a device/software)

Pen detected when connected?

Smooth writing with no lag?

Pressure sensitivity works?

Eraser/back button works?

Works across supported apps?

Battery/charging indicator works?

Calibration accurate?
