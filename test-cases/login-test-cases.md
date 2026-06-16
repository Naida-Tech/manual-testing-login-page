# Login Test Cases

## Application Under Test

**Application:** The Internet – Login Page
**Feature:** Login functionality
**Testing Type:** Manual Testing

---

## TC-001: Login with valid credentials

**Precondition:**
User is on the login page.

**Test Steps:**

1. Enter valid username: `tomsmith`
2. Enter valid password: `SuperSecretPassword!`
3. Click the Login button.

**Expected Result:**
User should be successfully logged in and redirected to the secure area.

**Actual Result:**
User was successfully logged in and redirected to the secure area.

**Status:** Pass

---

## TC-002: Login with invalid username

**Precondition:**
User is on the login page.

**Test Steps:**

1. Enter invalid username: `wronguser`
2. Enter valid password: `SuperSecretPassword!`
3. Click the Login button.

**Expected Result:**
User should not be logged in and an error message should be displayed.

**Actual Result:**
User was not logged in and an error message was displayed.

**Status:** Pass

---

## TC-003: Login with invalid password

**Precondition:**
User is on the login page.

**Test Steps:**

1. Enter valid username: `tomsmith`
2. Enter invalid password: `WrongPassword123`
3. Click the Login button.

**Expected Result:**
User should not be logged in and an error message should be displayed.

**Actual Result:**
User was not logged in and an error message was displayed.

**Status:** Pass

---

## TC-004: Login with empty fields

**Precondition:**
User is on the login page.

**Test Steps:**

1. Leave the username field empty.
2. Leave the password field empty.
3. Click the Login button.

**Expected Result:**
User should not be logged in and an error message should be displayed.

**Actual Result:**
User was not logged in and an error message was displayed.

**Status:** Pass

---

## TC-005: Logout after successful login

**Precondition:**
User is successfully logged in.

**Test Steps:**

1. Click the Logout button.

**Expected Result:**
User should be logged out and redirected back to the login page.

**Actual Result:**
User was logged out and redirected back to the login page.

**Status:** Pass
