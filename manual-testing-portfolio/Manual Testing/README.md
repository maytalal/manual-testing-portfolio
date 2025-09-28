# Manual Testing Project - TO DO Cart Application

## 📋 Project Overview
Comprehensive manual testing suite for a TO DO cart web application, covering functional, UI, and negative test scenarios.

## 🎯 Testing Scope
- **Signup Module** - User registration functionality
- **Login Module** - User authentication 
- **To Do Module** - Task management features
- **Cross-browser Compatibility** - Chrome, Firefox, Edge

## 📊 Test Cases Summary

### ✅ Signup Module (30 Test Cases)
- **TC_001** - Verify signup with valid credentials
- **TC_002** - Verify signup with First name more than 3 characters
- **TC_003** - Verify signup with First name contains only two characters
- **TC_004** - Verify signup with First name contains exactly 3 characters
- **TC_005** - Verify signup with First name contains digits
- **TC_006** - Verify signup with Last name contains digits
- **TC_007** - Verify signup with Last name contains exactly 3 characters
- **TC_008** - Verify signup with Last name contains 2 characters
- **TC_009** - Verify signup with Last name more than 3 characters
- **TC_010** - Verify signup with Last name contains digits
- **TC_011** - Verify signup with email with wrong format
- **TC_012** - Verify signup with copy/paste email
- **TC_013** - Verify signup with password less than 8 characters
- **TC_014** - Verify signup with password without upper letter
- **TC_015** - Verify signup with password without lower letter
- **TC_016** - Verify signup with password without special characters
- **TC_017** - Verify signup with password without digit
- **TC_018** - Verify signup with password exactly 8 characters
- **TC_019** - Verify signup with mismatch password
- **TC_020** - Verify signup with empty First name
- **TC_021** - Verify signup with empty Last name
- **TC_022** - Verify signup with empty email
- **TC_023** - Verify signup with empty password
- **TC_024** - Verify signup with empty confirm password
- **TC_025** - Verify Redirection "Do you have an Account?"
- **TC_026** - Verify Redirection "Login"
- **TC_027** - Verify Redirection "Signup"
- **TC_028** - Verify Signup with long firstname (250 character)
- **TC_029** - Verify Signup with long Last name (250 character)
- **TC_030** - Verify Signup with Registered Account

### ✅ Login Module (8 Test Cases)
- **TC_001** - Verify login with valid email and password
- **TC_002** - Verify login with valid email and incorrect password
- **TC_003** - Verify login with invalid email (not registered before)
- **TC_004** - Verify login with empty email
- **TC_005** - Verify login with empty password
- **TC_006** - Verify redirection to "To do page" after login
- **TC_007** - Verify redirection to "Create a new Account?"
- **TC_008** - Verify "loader location" when click login

### ✅ To Do Module (12 Test Cases)
- **TC_001** - Verify Welcome message according to time
- **TC_002** - Verify Adding new Todos Task more than 3 characters
- **TC_003** - Verify Adding new Todos Task contains only 2 characters
- **TC_004** - Verify Adding new Todos Task contains exactly 3 characters
- **TC_005** - Verify Banner appearance
- **TC_006** - Verify Logout Button
- **TC_007** - Verify Home Button
- **TC_008** - Verify TODO Button
- **TC_009** - Verify delete task
- **TC_010** - Verify check task and Strikethrough the task
- **TC_011** - Verify "Go back to your Todos"
- **TC_012** - Check the Design

## 🐛 Critical Bugs Discovered

### 🔴 High Priority Bugs
1. **First/Last name accepts digits** - Security/Validation issue
2. **Registration with extremely long names (250 chars)** - Performance/Security risk
3. **First name rejects exactly 3 characters** - Business logic error
4. **Loader appears in wrong location** - UI/UX issue
5. **"No Available Todos" message doesn't disappear** - UI bug

## 📈 Test Results

| Module | Total Cases | Passed | Failed | Success Rate |
|--------|-------------|--------|--------|--------------|
| Signup | 30 | 25 | 5 | 83.3% |
| Login | 8 | 7 | 1 | 87.5% |
| To Do | 12 | 11 | 1 | 91.7% |
| **Total** | **50** | **43** | **7** | **86%** |

## 🛠 Testing Techniques Applied

- **Boundary Value Analysis** (2, 3, 4+ characters testing)
- **Equivalence Partitioning** (Valid/Invalid inputs)
- **Negative Testing** (Invalid scenarios)
- **UI/UX Validation** (Design and user experience)
- **Cross-browser Testing** (Chrome, Firefox, Edge)
- **Regression Testing** (Re-testing after fixes)

## 🎖 Skills Demonstrated

- **Comprehensive Test Coverage** - 50+ test cases
- **Bug Investigation** - Critical issues identification
- **Documentation** - Detailed test case writing
- **Analytical Thinking** - Edge cases discovery
- **Quality Assurance** - End-to-end testing approach
