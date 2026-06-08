# REP-0003: Reports testing - Verify Active Permit Count

> Summary: Verify that the reports page displays the correct number of active chainsaw permits.

**Preconditions:** The tester is logged in to Chainventory using a valid account and at least one active chainsaw permit record exists.

**Scenario 1**

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Open the Chainventory website. | Verify that the system loads successfully. |
| 2 | Log in using a valid account, if needed. | Verify that the user is redirected to the dashboard. |
| 3 | Click the `Reports` navigation link or button. | Verify that the reports page opens successfully. |
| 4 | Locate the `Active Permits` report card or section. | Verify that the active permits value is visible. |
| 5 | Check the displayed active permits value. | Verify that the value is readable and not blank. |
| 6 | Compare the value with the active records in the chainsaw records page, if applicable. | Verify that the active permits count matches the active records available to the user. |

**Post-conditions:**

* The reports page displays the number of active permits.
* The active permit count is clear and understandable to the user.
