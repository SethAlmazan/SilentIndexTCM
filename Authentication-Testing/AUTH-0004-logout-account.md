# AUTH-0004: Authentication testing - Logout Account

> Summary: Verify that a logged-in user can log out successfully.

**Preconditions:** The tester is logged in to Chainventory using a valid account.

**Scenario 1**

| # | Step                                                          | Expected Behavior                                                                    |
| - | ------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| 1 | Launch the Chainventory website.                              | Verify that the dashboard is shown.                                                  |
| 2 | Locate the `Logout` button or logout option.                  | Verify that the logout option is visible to the user.                                |
| 3 | Click the `Logout` button or logout option.                   | Verify that the logout action is triggered.                                          |
| 4 | Confirm logout, if a confirmation modal appears.              | Verify that the system proceeds with the logout process.                             |
| 5 | Wait for the system response.                                 | Verify that the user is redirected to the login page.                                |
| 6 | Try to return to the dashboard using the browser back button. | Verify that the user cannot access the protected dashboard without logging in again. |

**Post-conditions:**

* The user is logged out successfully.
* Protected pages require login again before access.
