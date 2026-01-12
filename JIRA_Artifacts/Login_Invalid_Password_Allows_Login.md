# BUG: Login succeeds with invalid password

## Bug ID
BAMT-31

## Module
Login & Authentication

## Priority
High

## Severity
Critical (Security Issue)

## Environment
- Application: Banking Application
- Build: v1.0
- Browser: Chrome
- OS: Windows 10

## Preconditions
- User account exists
- Account is active

## Steps to Reproduce
1. Open the banking application
2. Navigate to Login page
3. Enter valid username
4. Enter invalid password
5. Click Login

## Actual Result
User is logged in successfully.

## Expected Result
User should see an error message:  
**"Invalid username or password"**

## Impact
This is a serious security issue as unauthorized users can access accounts.

## JIRA Evidence

## Defect Management (JIRA)

This project demonstrates real-world defect tracking using JIRA.

### Sample Bug Raised
- **Bug ID:** BAMT-31
- **Title:** Login succeeds with invalid password
- **Severity:** Critical
- **Tool Used:** JIRA
- **Evidence:** Screenshots and bug report available under  
  `JIRA_Artifacts/Bug_Reports/Login_Module`

See screenshot:  
`BUG-Login_InvalidPassword_AllowsLogin.png`
