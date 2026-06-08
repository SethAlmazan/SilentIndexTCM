# AUTH-0002: Authentication testing - Login with Valid Account

> Summary: Verify that a registered user can log in successfully using valid credentials.

**Preconditions:** The tester has a valid Chainventory account and is currently logged out.

**Scenario 1**

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Launch the Chainventory website. | Verify that the login page is shown. |
| 2 | Enter a valid email address. | Verify that the email field accepts the input. |
| 3 | Enter the correct password. | Verify that the password field accepts the input. |
| 4 | Click the `Login` or `Sign In` button. | Verify that the login request is submitted. |
| 5 | Wait for the system response. | Verify that the user is redirected to the dashboard. |
| 6 | Check the dashboard page. | Verify that the user can access the protected Chainventory dashboard. |

**Post-conditions:**

* The user is logged in successfully.
* The dashboard is displayed.
