# AUTH-0005: Authentication testing - Protected Dashboard Access

> Summary: Verify that unauthenticated users cannot access the protected Chainventory dashboard.

**Preconditions:** The tester is not logged in to Chainventory.

**Scenario 1**

| # | Step                                                       | Expected Behavior                                                       |
| - | ---------------------------------------------------------- | ----------------------------------------------------------------------- |
| 1 | Open a browser where no Chainventory account is logged in. | Verify that there is no active user session.                            |
| 2 | Enter the direct dashboard URL in the address bar.         | Verify that the system checks the user session.                         |
| 3 | Wait for the page to load.                                 | Verify that the dashboard is not displayed to the unauthenticated user. |
| 4 | Observe the redirected page.                               | Verify that the user is redirected to the login page or sign-in page.   |
| 5 | Log in using a valid account.                              | Verify that the system allows access after successful authentication.   |
| 6 | Open the dashboard again.                                  | Verify that the dashboard is now accessible to the authenticated user.  |

**Post-conditions:**

* Unauthenticated users cannot access the dashboard.
* Authenticated users can access the dashboard after login.
