# RES-0004: Responsive testing - Record Details Mobile View

> Summary: Verify that the record details view displays properly on mobile screen sizes.

**Preconditions:** The tester is logged in to Chainventory using a valid account, at least one chainsaw record exists, and the tester is using a mobile device or browser mobile view.

**Scenario 1**

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Open the Chainventory website on a mobile device or browser mobile view. | Verify that the website loads successfully. |
| 2 | Log in using a valid account, if needed. | Verify that the user is redirected to the dashboard. |
| 3 | Navigate to the `Records` page. | Verify that the chainsaw records page opens successfully. |
| 4 | Select an existing chainsaw record. | Verify that the selected record is visible in the records list. |
| 5 | Click the `View` or eye icon action. | Verify that the record details modal or page opens. |
| 6 | Scroll through the record details. | Verify that all owner, chainsaw, and registration details are readable. |
| 7 | Check the uploaded images section. | Verify that proof of ownership and inspection images fit properly on mobile view. |
| 8 | Close the record details modal or page. | Verify that the user can return to the records list without layout issues. |

**Post-conditions:**

* Record details are readable on mobile view.
* Uploaded images and details are properly displayed on smaller screens.
