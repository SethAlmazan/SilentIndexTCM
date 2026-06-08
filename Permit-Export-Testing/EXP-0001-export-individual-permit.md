# EXP-0001: Export testing - Export Individual Chainsaw Permit

> Summary: Verify that the user can export an individual chainsaw permit from an existing chainsaw record.

**Preconditions:** The tester is logged in to Chainventory using a valid account and at least one chainsaw record exists.

**Scenario 1**

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Open the Chainventory website. | Verify that the system loads successfully. |
| 2 | Log in using a valid account, if needed. | Verify that the user is redirected to the dashboard. |
| 3 | Click the `Records` navigation link or button. | Verify that the chainsaw records page opens successfully. |
| 4 | Locate an existing chainsaw record in the records table. | Verify that the record is visible in the list. |
| 5 | Click the `Export` action for the selected record. | Verify that the export process starts. |
| 6 | Wait for the file to generate or download. | Verify that a Microsoft Word permit document is downloaded. |
| 7 | Open the downloaded permit file. | Verify that the file opens successfully and is not corrupted. |

**Post-conditions:**

* The selected chainsaw record is exported successfully.
* A Microsoft Word permit document is generated for the selected record.
