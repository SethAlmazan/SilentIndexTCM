# REC-0005: Records testing - Edit Existing Record

> Summary: Verify that the user can edit and update an existing chainsaw record.

**Preconditions:** The tester is logged in to Chainventory using a valid account and at least one chainsaw record exists.

**Scenario 1**

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Open the Chainventory website. | Verify that the system loads successfully. |
| 2 | Log in using a valid account, if needed. | Verify that the user is redirected to the dashboard. |
| 3 | Click the `Records` navigation link or button. | Verify that the chainsaw records page opens. |
| 4 | Locate an existing chainsaw record in the table. | Verify that the record is visible in the records list. |
| 5 | Click the `Edit` action for the selected record. | Verify that the edit record form or modal opens. |
| 6 | Update one or more editable fields. | Verify that the fields accept the updated information. |
| 7 | Click the `Save`. | Verify that the update request is submitted. |
| 8 | Wait for the system response. | Verify that the record is updated successfully. |
| 9 | Open the updated record details. | Verify that the updated information is displayed correctly. |

**Post-conditions:**

* The selected chainsaw record is updated successfully.
* The updated information is visible in the records list or record details.
