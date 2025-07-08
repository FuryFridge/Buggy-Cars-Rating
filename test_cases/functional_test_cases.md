# Functional Test Cases – Buggy Cars Rating

### ✅ Test Case ID: TC-01  
**Title:** Register a new user with valid data

- **Preconditions:**  
  User is logged out and on the "Register" page.

- **Test Steps:**  
  1. Open the Buggy Cars Rating homepage.  
  2. Click on the "Register" button to be redirrected to Register page.  
  3. Enter a unique Login in "Login" field.  
  4. Enter a valid first and last name in relevant fields.  
  5. Enter a strong password (e.g., `Buggy123!`).  
  6. Confirm the password correctly.  
  7. Click the "Register" button.

- **Expected Result:**  
  User see the message that registeration is successfull.

- **Actual Result:**  
  _[To be filled during execution]_

- **Status:**  
  _[Pass / Fail / Blocked / Caution]_

- **Severity:**  
  Medium

---

### ⚠️ Test Case ID: TC-02  
**Title:** Register with an existing username

- **Preconditions:**  
  A user with the same username already exists in the system.

- **Test Steps:**
  1. Open the Buggy Cars Rating homepage.  
  2. Click on the "Register" button to be redirrected to Register page.  
  3. Enter a username that already exists (e.g.`CarsToTest`).  
  3. Fill in valid data in the other fields.  
  4. Submit the registration form.

- **Expected Result:**  
  An error message is displayed indicating the username already exists.

- **Actual Result:**  
  _[To be filled during execution]_

- **Status:**  
  _[Pass / Fail / Blocked / Caution]_

- **Severity:**  
  High

---

### ⚠️ Test Case ID: TC-03  
**Title:** Register with blank required input fields

- **Preconditions:**  
  User is on the "Register" page.

- **Test Steps:**  
  1. Leave one or more required fields blank (e.g., username, password, first name).  
  2. Verify that user is unnable to click "Register" button with error message appearing under blank field(s).

- **Expected Result:**  
  The system displays error messages indicating which required fields are missing.

- **Actual Result:**  
  _[To be filled during execution]_

- **Status:**  
  _[Pass / Fail / Blocked / Caution]_

- **Severity:**  
  Medium

---

### ⚠️ Test Case ID: TC-04  
**Title:** Register with mismatched passwords

- **Preconditions:**  
  User is on the "Register" page.

- **Test Steps:**  
  1. Enter valid data in all fields except: "Password" and "Confirm Password".
  2. Verify that user is unnable to click "Register" button with error message "Passwords do not match" appearing.

- **Expected Result:**  
  The system displays an error message indicating the passwords do not match.

- **Actual Result:**  
  _[To be filled during execution]_

- **Status:**  
  _[Pass / Fail / Blocked / Caution]_

- **Severity:**  
  Medium

---

### ✅ Test Case ID: TC-06  
**Title:** Login with valid credentials

- **Preconditions:**  
  A user account exists with known credentials. User is on the "Login" page.

- **Test Steps:**  
  1. Open the Buggy Cars Rating homepage.  
  2. Populate the Login field with relevant Login name.  
  3. Populate the Password field with relevant password.
  4. Click "Login" button.

- **Expected Result:**  
  User is successfully logged in and "Welcome, username" message appears instead of Login/Password fields.

- **Actual Result:**  
  _[To be filled during execution]_

- **Status:**  
  _[Pass / Fail / Blocked / Caution]_

- **Severity:**  
  High

---

### ❌ Test Case ID: TC-07  
**Title:** Login with invalid credentials

- **Preconditions:**  
  User is on the "Login" page.

- **Test Steps:**  
  1. Enter a valid username with an incorrect password.
  2. Click "Login" button.

- **Expected Result:**  
  Login fails. An appropriate error message is displayed (e.g., "Invalid username/password").

- **Actual Result:**  
  _[To be filled during execution]_

- **Status:**  
  _[Pass / Fail / Blocked / Caution]_

- **Severity:**  
  High

---

### ✅ Test Case ID: TC-08  
**Title:** Logout from the application

- **Preconditions:**  
  User is logged in.

- **Test Steps:**  
  1. Click on the "Logout" button at the top left corner.

- **Expected Result:**  
  User is logged out and redirected to the login or home page. Session should be terminated.

- **Actual Result:**  
  _[To be filled during execution]_

- **Status:**  
  _[Pass / Fail / Blocked / Caution]_

- **Severity:**  
  Medium

---

### ✅ Test Case ID: TC-09  
**Title:** View user profile

- **Preconditions:**  
  User is logged in.

- **Test Steps:**  
  1. Click on the "Profile" link in the navigation bar.

- **Expected Result:**  
  User profile page is displayed with correct personal information.

- **Actual Result:**  
  _[To be filled during execution]_

- **Status:**  
  _[Pass / Fail / Blocked / Caution]_

- **Severity:**  
  Low

---

### ⚙️ Test Case ID: TC-10  
**Title:** Update user profile details

- **Preconditions:**  
  User is logged in and on the "Profile" page.

- **Test Steps:**  
  1. Edit the first name or last name fields.  
  2. Click the "Save" or button.

- **Expected Result:**  
  Profile details are successfully updated and saved.

- **Actual Result:**  
  _[To be filled during execution]_

- **Status:**  
  _[Pass / Fail / Blocked / Caution]_

- **Severity:**  
  Medium
