# IMG-0003: Image upload testing - Remove Selected Image Before Submit

> Summary: Verify that the user can remove a selected image before submitting the registration form.

**Preconditions:** The tester is logged in to Chainventory using a valid account and is on the chainsaw registration page.

**Scenario 1**

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Open the Chainventory website. | Verify that the system loads successfully. |
| 2 | Log in using a valid account, if needed. | Verify that the user is redirected to the dashboard. |
| 3 | Navigate to the `Registration` page. | Verify that the chainsaw registration form is displayed. |
| 4 | Select one or more valid image files in the proof of ownership or inspection image upload section. | Verify that the selected images are accepted and displayed in the preview area. |
| 5 | Locate the remove button or `X` button on one selected image. | Verify that the remove option is visible. |
| 6 | Click the remove button or `X` button. | Verify that the selected image is removed from the preview list. |
| 7 | Check the remaining selected images, if any. | Verify that the other selected images remain in the preview list. |
| 8 | Submit the form with valid information. | Verify that only the remaining selected images are uploaded. |

**Post-conditions:**

* The user can remove a selected image before submitting the form.
* Removed images are not included in the final uploaded images.
