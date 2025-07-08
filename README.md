# Buggy-Cars-Rating

The primary goal of this project is to design and implement a complete QA test suite for the public demo application Buggy Cars Rating, simulating the responsibilities of a real QA Engineer working in an Agile team.

This project is based on Buggy Cars Rating Website (https://buggy.justtestit.org/) which is perfect example, because the site is deliberately designed to be buggy.
The app supports full CRUD-like functionality and real user interaction flows:
* User Registration/Login - Auth testing, validation scenarios
* Rate a Car - Form testing, input handling, data validation
* View Top Rated Cars - Backend API, sorting, UI correctness
* Update Password/Profile - Security testing, state change, field checks
* Session management - Cookie handling, session timeout (if any), logout handling

The idea of the project is to cover all major aspects of Quality Assurance — from functional and UI testing to API validation, performance analysis, and user-centric testing (UAT). The project combines manual test case design and automated test execution using **Java**, **TestNG**, **Selenium**, and **Rest-Assured**.

## Types of Testing in the Buggy Cars Rating QA Project

### 1. Functional Testing

**Goal:**  
Verify that all features of the application work as expected under valid and invalid conditions.

**✅ What will be tested:**
- User registration, login, logout
- Submitting a car rating
- Viewing popular cars and car details
- Updating profile and password
- Error handling (e.g., wrong login, missing fields)

**Tools:**  
Manual test cases, automated tests using **Java + Selenium + TestNG**

---

### 2. API Testing

**Goal:**  
Validate the backend logic and data by interacting directly with API endpoints.

**✅ What will be tested:**
- Login API (form auth)
- Get popular cars API
- Submit car rating API
- Check response codes, JSON responses, headers, and performance

**Tools:**  
**Rest-Assured + Java + TestNG**

---

### 3. UI Automation Testing

**Goal:**  
Automatically test key user flows and reduce repetitive manual testing.

**✅ What will be automated:**
- Login and logout
- Register new users
- Submit ratings
- Change password
- Verify popular car lists

**Tools:** 
**Selenium WebDriver**, **TestNG**, **Page Object Model (POM)**

---

### 4. Usability Testing

**Goal:**   
Evaluate how user-friendly and intuitive the application is.

**✅ What will be checked:**
- Clarity of error messages and field validation
- Feedback after user actions
- Button labels, layout consistency
- Form design and input behavior

**Tools:**  
Manual evaluation, checklist in `usability_review.md`

---

### 5. Performance Testing

**Goal:** 
Assess the speed, stability, and responsiveness of the frontend and APIs.

**✅ What will be measured:**
- Page load speed (homepage, car detail page)
- API response time (e.g., submit rating)
- Lighthouse performance scores

**Tools:**  
Google Lighthouse, Rest-Assured (timing), Chrome DevTools

---

### 6. User Acceptance Testing (UAT)

**Goal:** 
Simulate real-world user scenarios to verify that business flows work end-to-end.

**✅ Scenarios:**
- Register → Login → Rate a Car → Logout
- Login → Change Password → Login with New Password
- Login → Submit Invalid Rating → Verify Error

**Tools:** 
Manual execution, documented in `uat_scenarios.md`

---

## ✅ Summary Table

| Type               | Tool(s)                      | Output                                           |
|--------------------|------------------------------|--------------------------------------------------|
| Functional         | Selenium, TestNG             | Manual & Automated Test Cases                   |
| API                | Rest-Assured, TestNG         | API Test Classes, Postman Collection (optional) |
| UI Automation      | Selenium + POM + TestNG      | Reusable Automation Suite                       |
| Usability          | Manual Review                | Markdown Report                                 |
| Performance        | Lighthouse, Rest-Assured     | Reports + API Timings                           |
| UAT                | Manual, Checklist            | User Journey Docs                               |
