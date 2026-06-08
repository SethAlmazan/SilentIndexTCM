# REP-0002: Reports testing - Verify Total Registration Count

> Summary: Verify that the reports page displays the correct total number of chainsaw registrations.

**Preconditions:** The tester is logged in to Chainventory using a valid account and at least one chainsaw record exists.

**Scenario 1**

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Open the Chainventory website. | Verify that the system loads successfully. |
| 2 | Log in using a valid account, if needed. | Verify that the user is redirected to the dashboard. |
| 3 | Click the `Reports` navigation link or button. | Verify that the reports page opens successfully. |
| 4 | Locate the `Total Registrations` report card or section. | Verify that the total registrations value is visible. |
| 5 | Check the displayed total registrations value. | Verify that the value is readable and not blank. |
| 6 | Compare the value with the number of available chainsaw records, if applicable. | Verify that the total registrations count matches the records available to the user. |

**Post-conditions:**

* The reports page displays the total number of chainsaw registrations.
* The displayed count is clear and understandable to the user.
