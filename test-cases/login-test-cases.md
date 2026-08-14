# Login Test Cases

## TC-001 — Successful login with valid credentials

**Preconditions:** User has a registered account.

**Steps:**
1. Open the login page.
2. Enter a valid email.
3. Enter a valid password.
4. Click the "Login" button.

**Expected Result:** User is successfully logged in and redirected to the account page.

**Priority:** High

---

## TC-002 — Login with incorrect password

**Preconditions:** User has a registered account.

**Steps:**
1. Open the login page.
2. Enter a valid email.
3. Enter an incorrect password.
4. Click the "Login" button.

**Expected Result:** An error message is displayed and the user is not logged in.

**Priority:** High

---

## TC-003 — Login with unregistered email

**Steps:**
1. Open the login page.
2. Enter an unregistered email.
3. Enter any password.
4. Click the "Login" button.

**Expected Result:** An error message is displayed and the user is not logged in.

**Priority:** High

---

## TC-004 — Login with empty email field

**Steps:**
1. Open the login page.
2. Leave the email field empty.
3. Enter a valid password.
4. Click the "Login" button.

**Expected Result:** Validation message is displayed for the email field.

**Priority:** Medium

---

## TC-005 — Login with empty password field

**Steps:**
1. Open the login page.
2. Enter a valid email.
3. Leave the password field empty.
4. Click the "Login" button.

**Expected Result:** Validation message is displayed for the password field.

**Priority:** Medium

---

## TC-006 — Login with both fields empty

**Steps:**
1. Open the login page.
2. Leave the email and password fields empty.
3. Click the "Login" button.

**Expected Result:** Validation messages are displayed for the required fields.

**Priority:** Medium

---

## TC-007 — Password is hidden

**Steps:**
1. Open the login page.
2. Enter a password into the password field.

**Expected Result:** Password characters are masked and are not displayed as plain text.

**Priority:** Low

---

## TC-008 — Login button is available

**Steps:**
1. Open the login page.
2. Check the login form.

**Expected Result:** The "Login" button is visible and available to the user.

**Priority:** Medium

---

## TC-009 — Email format validation

**Steps:**
1. Open the login page.
2. Enter an invalid email format, for example `test@`.
3. Enter any password.
4. Click the "Login" button.

**Expected Result:** A validation message is displayed indicating that the email format is invalid.

**Priority:** Medium

---

## TC-010 — Successful logout

**Preconditions:** User is logged in.

**Steps:**
1. Open the user account menu.
2. Click "Logout".

**Expected Result:** User is logged out and redirected to the login page.

**Priority:** High
