# EXP-0002: Export testing - Verify Exported Permit Information Matches Chainsaw Records

> Summary: Verify that all information in the exported chainsaw permit matches the information saved in the chainsaw records.

**Preconditions:** The tester is logged in to Chainventory using a valid account, at least one chainsaw record exists, and an individual permit has been exported.

**Scenario 1**

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Open the Chainventory website. | Verify that the system loads successfully. |
| 2 | Log in using a valid account, if needed. | Verify that the user is redirected to the dashboard. |
| 3 | Go to the `Records` page. | Verify that the chainsaw records page opens successfully. |
| 4 | Select an existing chainsaw record. | Verify that the selected record is visible in the records list. |
| 5 | Open the record details. | Verify that the complete chainsaw record information is displayed. |
| 6 | Export the selected chainsaw permit. | Verify that a Microsoft Word permit document is downloaded or generated. |
| 7 | Open the exported Microsoft Word file. | Verify that the exported permit file opens successfully and is readable. |
| 8 | Compare the owner information in the exported permit with the record details. | Verify that the owner information matches the saved chainsaw record. |
| 9 | Compare the chainsaw information in the exported permit with the record details. | Verify that the brand, model, serial number, power rating, length, origin/source, and price match the saved chainsaw record. |
| 10 | Compare the registration details in the exported permit with the record details. | Verify that the registration number, purpose, area/location, registration date, expiry date, and status match the saved chainsaw record. |
| 11 | Check the inspection images in the exported permit. | Verify that the exported permit includes the correct inspection images from the selected record. |
| 12 | Review the exported permit layout. | Verify that all exported information is readable, complete, and properly formatted. |

**Post-conditions:**

* The exported permit information matches the selected chainsaw record.
* The exported Microsoft Word permit is readable and properly formatted.
