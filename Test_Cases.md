# Login Module Test Cases

## TC_LOGIN_001 - Verify login with valid customer credentials

Precondition:
Customer account should be active.

Test Steps:
1. Open Banking Portal
2. Enter valid Customer ID
3. Enter valid Password
4. Click Login

Expected Result:
Customer should be redirected to Account Summary page.

Priority:
High

Status:
Pass

---

## TC_LOGIN_002 - Verify login with invalid password

Test Steps:
1. Enter valid Customer ID
2. Enter invalid Password
3. Click Login

Expected Result:
System should display "Invalid Credentials" message.

Priority:
High

Status:
Pass

---

## TC_LOGIN_003 - Verify login with blank password field

Expected Result:
Validation message should be displayed.
