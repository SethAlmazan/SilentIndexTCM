# AUTH-0003: Authentication testing - Login with Invalid Password

> Summary: Verify that the system prevents login when the user enters an invalid password.

**Preconditions:** The tester has an existing Chainventory account and is currently logged out.

**Scenario 1**

| # | Step                                   | Expected Behavior                                                   |
| - | -------------------------------------- | ------------------------------------------------------------------- |
| 1 | Launch the Chainventory website.       | Verify that the login page is shown.                                |
| 2 | Enter a registered email address.      | Verify that the email field accepts the input.                      |
| 3 | Enter an incorrect password.           | Verify that the password field accepts the input.                   |
| 4 | Click the `Login` or `Sign In` button. | Verify that the login request is submitted.                         |
| 5 | Wait for the system response.          | Verify that the user is not redirected to the dashboard.            |
| 6 | Check for an error message.            | Verify that the system displays an appropriate login error message. |
| 7 | Check the current page.                | Verify that the user remains on the login page.                     |

**Post-conditions:**

* The user is not logged in.
* The system prevents access using an invalid password.
