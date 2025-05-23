# Task Log – Microsoft 365 Admin Lab

This file logs all the core tasks performed during the Microsoft 365 Admin Center simulation.

---

## 🧑‍💼 Task: Add New Users

- Added three users:
  - Rithesh Baroor (rithesh@labdomain.onmicrosoft.com)
  - John Doe (john@labdomain.onmicrosoft.com)
  - Alice Smith (alice@labdomain.onmicrosoft.com)
- Default password set with "Require password change on next sign-in" enabled.

---

## 🎫 Task: Assign Microsoft 365 E5 Licenses

- Assigned Microsoft 365 E5 Developer licenses to all three users.
- Verified services like Exchange, Teams, and OneDrive were enabled.

---

## 🔐 Task: Reset Password

- Reset Alice Smith’s password via Admin Center → Users → Reset Password.
- Sent temporary password manually for test login.

---

## 🔄 Task: Set Password Expiration Policy

- Navigated to Azure AD → Password Reset.
- Configured password expiration to 60 days with 14-day warning.

---

## 🔑 Task: Enable Multi-Factor Authentication (MFA)

- Enabled MFA for John Doe via Azure Portal → Users → Multi-Factor Authentication.
- Tested login on InPrivate window – verified with phone prompt.

---

## 👥 Task: Create Security Group

- Created group: “Helpdesk Team”
- Added Rithesh and John to the group
- Group type: Security; membership type: Assigned

---

## 🔐 Task: Test Login with MFA

- Logged in as John Doe
- Verified: password change → MFA phone verification → access granted

---

All tasks were executed within a Microsoft 365 Developer E5 environment using Admin Center and Azure AD.

