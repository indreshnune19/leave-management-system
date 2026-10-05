# BUG-001 — Incorrect Employee spelling on Login page

## Bug Information

| Field                 | Details                                           |
| --------------------- | ------------------------------------------------- |
| **Bug ID**            | BUG-001                                           |
| **Title**             | Employee is misspelled as "Employe" on Login page |
| **Module**            | Authentication / Login                            |
| **Related Test Case** | TC-001                                            |
| **Related Scenario**  | TS-001                                            |
| **Bug Type**          | UI / Text Validation                              |
| **Severity**          | Minor                                             |
| **Priority**          | Medium                                            |
| **Environment**       | Local / Development                               |
| **Status**            | New                                               |
| **Reproducible**      | Yes                                               |

## Preconditions

1. Leave Management System is running.
2. Login page is accessible.

## Steps to Reproduce

1. Open the Leave Management System.
2. Navigate to the Login page.
3. Locate the Employee ID field.
4. Observe the field label.

## Test Data

N/A

## Expected Result

The Employee ID field label should be displayed correctly as:

**Employee ID**

## Actual Result

The Employee ID field label is displayed as:

**Employe ID**

The word **"Employee"** is missing the letter **"e"**.

## Evidence

Screenshot showing the incorrect **"Employe ID"** label:

https://github.com/user-attachments/assets/04cb0149-1a86-4e7f-82b3-cfa7d7a25dc9

## Impact

The spelling error is visible to users on the Login page and negatively affects the application's UI quality and professional appearance.

## Suggested Fix

Change:

**Employe ID**

to:

**Employee ID**

## Reproduction Status

**Reproducible: Yes**


Related Test Case

TC-001 — Verify Employee ID field is displayed
