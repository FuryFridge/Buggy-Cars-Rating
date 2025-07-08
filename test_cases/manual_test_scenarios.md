# Manual Test Scenarios – Buggy Cars Rating

**Project:** Buggy Cars Rating QA  
**Author:** Yuriy Chankov

---

## 🧍 User Account Scenarios

| ID    | Scenario                                           |
|-------|----------------------------------------------------|
| TC-01 | Register a new user with valid data                |
| TC-02 | Attempt to register with an existing username      |
| TC-03 | Register with invalid or empty input fields        |
| TC-04 | Login with valid credentials                       |
| TC-05 | Login with invalid credentials                     |
| TC-06 | Logout from the application                        |
| TC-07 | View user profile                                  |
| TC-08 | Update user profile details                        |
| TC-09 | Change password with correct current password      |
| TC-10 | Attempt to change password with incorrect password |

---

## 🚗 Car Rating & Browsing Scenarios

| ID    | Scenario                                                |
|-------|---------------------------------------------------------|
| TC-11 | View the list of top-rated cars                         |
| TC-12 | Navigate to a specific car's detail page                |
| TC-13 | Submit a car rating as a logged-in user                 |
| TC-14 | Attempt to submit a car rating without logging in       |
| TC-15 | Submit multiple ratings for the same car                |
| TC-16 | View comments or rating summary for a car               |

---

## ⚠️ Error Handling / Negative Scenarios

| ID    | Scenario                                                 |
|-------|----------------------------------------------------------|
| TC-17 | Register with mismatched passwords                       |
| TC-18 | Register with blank required fields                      |
| TC-19 | Attempt to update profile without logging in             |
| TC-20 | Attempt to change password without entering current pass |

---

## ✅ User Acceptance Test (UAT) Flows

| ID    | Scenario                                                             |
|-------|----------------------------------------------------------------------|
| TC-21 | Register → Login → Rate a car → Logout                              |
| TC-22 | Login → Change password → Logout → Login with new password          |
| TC-23 | Login → Attempt invalid rating → Verify system response             |

---

## 📝 Notes

- These scenarios will serve as the base for detailed test case development.
- Some scenarios will be automated later using Selenium/TestNG.
- Edge cases and additional negative tests will be added during execution phase.
