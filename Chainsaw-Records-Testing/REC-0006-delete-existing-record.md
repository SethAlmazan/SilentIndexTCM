# REC-0006: Records testing - Delete Existing Record

> Summary: Verify that the user can delete an existing chainsaw record.

**Preconditions:** The tester is logged in to Chainventory using a valid account and at least one chainsaw record exists.

**Scenario 1**

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Open the Chainventory website. | Verify that the system loads successfully. |
| 2 | Log in using a valid account, if needed. | Verify that the user is redirected to the dashboard. |
| 3 | Click the `Records` navigation link or button. | Verify that the chainsaw records page opens. |
| 4 | Locate an existing chainsaw record in the table. | Verify that the record is visible in the records list. |
| 5 | Click the `Delete` action for the selected record. | Verify that a delete confirmation message or modal appears. |
| 6 | Confirm the delete action. | Verify that the system processes the delete request. |
| 7 | Wait for the records table to update. | Verify that the deleted record is removed from the records list. |
| 8 | Search for the deleted record, if applicable. | Verify that the deleted record no longer appears in the records list. |

**Post-conditions:**

* The selected chainsaw record is deleted successfully.
* The deleted record is no longer visible in the records list.
