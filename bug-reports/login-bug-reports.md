# Login Bug Reports

## BUG-001 — Login button accepts empty fields

**Title:** Login form can be submitted with empty fields

**Environment:** Web application, Chrome

**Preconditions:** User is on the login page.

**Steps to Reproduce:**
1. Open the login page.
2. Leave the Email field empty.
3. Leave the Password field empty.
4. Click the "Login" button.

**Expected Result:**  
Validation messages are displayed for the required fields.

**Actual Result:**  
The form is submitted without displaying validation messages.

**Severity:** Medium

**Priority:** High


## BUG-002 — Invalid email format is accepted

**Title:** Login form accepts invalid email format

**Environment:** Web application, Chrome

**Preconditions:** User is on the login page.

**Steps to Reproduce:**
1. Open the login page.
2. Enter an invalid email, for example `test`.
3. Enter any password.
4. Click the "Login" button.

**Expected Result:**  
A validation message is displayed indicating that the email format is invalid.

**Actual Result:**  
The invalid email format is accepted by the form.

**Severity:** Medium

**Priority:** Medium


## BUG-003 — Logout does not redirect to login page

**Title:** User is not redirected to the login page after logout

**Environment:** Web application, Chrome

**Preconditions:** User is logged in.

**Steps to Reproduce:**
1. Log in to the application.
2. Open the user account menu.
3. Click "Logout".

**Expected Result:**  
The user is logged out and redirected to the login page.

**Actual Result:**  
The user is logged out, but remains on the current page.

**Severity:** High

**Priority:** High
