# REC-0002: Records testing - Search Chainsaw Records

> Summary: Verify that the user can search for chainsaw records using available record information.

**Preconditions:** The tester is logged in to Chainventory using a valid account and at least one chainsaw record exists.

**Scenario 1**

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Open the Chainventory website. | Verify that the system loads successfully. |
| 2 | Log in using a valid account, if needed. | Verify that the user is redirected to the dashboard. |
| 3 | Click the `Chainsaw Records` navigation link or button. | Verify that the chainsaw records page opens. |
| 4 | Locate the search input field. | Verify that the search field is visible and usable. |
| 5 | Enter an existing owner name, brand, model, serial number, or address keyword. | Verify that the search field accepts the input. |
| 6 | Observe the records table results. | Verify that matching records are displayed. |
| 7 | Enter a keyword that does not match any record. | Verify that no unrelated records are displayed. |
| 8 | Clear the search input field. | Verify that the full records list is displayed again. |

**Post-conditions:**

* The search function filters records based on the entered keyword.
* The records list returns to normal after clearing the search field.
