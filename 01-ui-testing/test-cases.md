TC-001
Title: Verify minimum allowed input length

Preconditions:
Input page is opened.

Steps:
1. Click the input field.
2. Enter "Aa".
3. Press Enter.

Expected Result:
The value is accepted and the form is submitted.

Status:

TC-002
Title: Verify maximum allowed input length

Preconditions:
Input page is opened.

Steps:
1. Click the input field.
2. Enter "qwertqwertyqwerty12345".
3. Press Enter.

Expected Result:
The value is accepted and the form is submitted.

Status:

TC-003
Title: Verify minimum forbidden input length

Preconditions:
Input page is opened.

Steps:
1. Click the input field.
2. Enter "A".
3. Press Enter.

Expected Result:
The value isn't accepted.

Status:

TC-003
Title: Verify maximum forbidden input length

Preconditions:
Input page is opened.

Steps:
1. Click the input field.
2. Enter "qwertqwertyqwerty123456".
3. Press Enter.

Expected Result:
The value isn't accepted.

Status:

TC-
