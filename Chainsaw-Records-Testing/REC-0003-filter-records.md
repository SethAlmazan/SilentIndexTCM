# REC-0003: Records testing - Filter Chainsaw Records

> Summary: Verify that the user can filter chainsaw records based on available filter options.

**Preconditions:** The tester is logged in to Chainventory using a valid account and multiple chainsaw records exist.

**Scenario 1**

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Open the Chainventory website. | Verify that the system loads successfully. |
| 2 | Log in using a valid account, if needed. | Verify that the user is redirected to the dashboard. |
| 3 | Click the `Records` navigation link or button. | Verify that the chainsaw records page opens. |
| 4 | Locate the filter option on the records page. | Verify that the filter option is visible and usable. |
| 5 | Select an available filter value, such as `Active`, or `Expired`. | Verify that the selected filter is applied. |
| 6 | Observe the records table. | Verify that only records matching the selected filter are displayed. |
| 7 | Change the selected filter to another value. | Verify that the records table updates based on the new filter. |
| 8 | Reset or clear the filter. | Verify that the full records list is displayed again. |

**Post-conditions:**

* The records table displays records based on the selected filter.
* The full records list is restored after clearing the filter.
