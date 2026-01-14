#### **Test Case 1: Patient Registration**



| \*\*Field\*\*       | \*\*Description\*\*                 |

| --------------- | ------------------------------- |

| Test Case ID    | TC\_HC\_Patient\_01                |

| Test Case Title | Verify patient registration     |

| Module Name     | Patient Registration            |

| Preconditions   | System should be accessible     |

| Test Steps      | 1. Open registration form       |

|                 | 2. Enter patient details        |

|                 | 3. Click Submit                 |

| Test Data       | Name: Rahul                     |

|                 | Age: 30                         |

| Expected Result | Patient registered successfully |

| Actual Result   | Registration successful         |

| Status          | Pass                            |

| Remarks         | Registration working            |





#### **Test Case 2: Appointment Booking**



| \*\*Field\*\*       | \*\*Description\*\*                 |

| --------------- | ------------------------------- |

| Test Case ID    | TC\_HC\_Appointment\_02            |

| Test Case Title | Verify appointment booking      |

| Module Name     | Appointment                     |

| Preconditions   | Patient must be registered      |

| Test Steps      | 1. Select doctor                |

|                 | 2. Select date                  |

|                 | 3. Click Book                   |

| Test Data       | Doctor: Dr. Sharma              |

| Expected Result | Appointment booked              |

| Actual Result   | Appointment booked successfully |

| Status          | Pass                            |

| Remarks         | Appointment module works        |





#### **Test Case 3: Invalid Appointment Date**



| \*\*Field\*\*       | \*\*Description\*\*               |

| --------------- | ----------------------------- |

| Test Case ID    | TC\_HC\_Appointment\_03          |

| Test Case Title | Verify booking with past date |

| Module Name     | Appointment                   |

| Preconditions   | Patient logged in             |

| Test Steps      | 1. Select past date           |

|                 | 2. Click Book                 |

| Test Data       | Date: Past date               |

| Expected Result | Error message shown           |

| Actual Result   | Error message displayed       |

| Status          | Pass                          |

| Remarks         | Date validation correct       |



