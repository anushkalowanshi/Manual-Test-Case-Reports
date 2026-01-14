#### **Test Case 1: Valid Login**





| \*\*Field\*\*       | \*\*Description\*\*                         |

| --------------- | --------------------------------------- |

| Test Case ID    | TC\_CRM\_Login\_01                         |

| Test Case Title | Verify login with valid credentials     |

| Module Name     | Login                                   |

| Preconditions   | User must be registered in CRM          |

| Test Steps      | 1. Open CRM login page                  |

|                 | 2. Enter valid username                 |

|                 | 3. Enter valid password                 |

|                 | 4. Click Login                          |

| Test Data       | Username: admin                         |

|                 | Password: admin@123                     |

| Expected Result | User should be logged in successfully   |

| Actual Result   | Logged in successfully                  |

| Status          | Pass                                    |

| Remarks         | Login functionality working as expected |





#### **Test Case 2: Blank Credentials**



| \*\*Field\*\*       | \*\*Description\*\*                     |

| --------------- | ----------------------------------- |

| Test Case ID    | TC\_CRM\_Login\_02                     |

| Test Case Title | Verify login with blank credentials |

| Module Name     | Login Validation                    |

| Preconditions   | Login page must be open             |

| Test Steps      | 1. Open CRM login page              |

|                 | 2. Leave username blank             |

|                 | 3. Leave password blank             |

|                 | 4. Click Login                      |

| Test Data       | Username: blank                     |

|                 | Password: blank                     |

| Expected Result | Error message should be displayed   |

| Actual Result   | Login failed message displayed      |

| Status          | Pass                                |

| Remarks         | Mandatory field validation working  |





#### **Test Case 3: Add New Customer**



| \*\*Field\*\*       | \*\*Description\*\*                                |

| --------------- | ---------------------------------------------- |

| Test Case ID    | TC\_CRM\_Customer\_01                             |

| Test Case Title | Verify adding a new customer                   |

| Module Name     | Customer Management                            |

| Preconditions   | User must be logged in                         |

| Test Steps      | 1. Click Add Customer                          |

|                 | 2. Enter customer details                      |

|                 | 3. Click Save                                  |

| Test Data       | Name: John                                     |

|                 | Email: \[john@gmail.com](mailto:john@gmail.com) |

| Expected Result | Customer should be added successfully          |

| Actual Result   | Customer added successfully                    |

| Status          | Pass                                           |

| Remarks         | Customer creation successful                   |







