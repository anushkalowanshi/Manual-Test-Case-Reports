#### **Test Case 1: Search Flights**



| \*\*Field\*\*       | \*\*Description\*\*                       |

| --------------- | ------------------------------------- |

| Test Case ID    | TC\_TBP\_Search\_01                      |

| Test Case Title | Verify flight search functionality    |

| Module Name     | Flight Search                         |

| Preconditions   | User must be on home page             |

| Test Steps      | 1. Enter source and destination       |

|                 | 2. Select date                        |

|                 | 3. Click Search                       |

| Test Data       | Source: Delhi                         |

|                 | Destination: Mumbai                   |

| Expected Result | Available flights should be displayed |

| Actual Result   | Flight list displayed                 |

| Status          | Pass                                  |

| Remarks         | Search working properly               |





#### **Test Case 2: Invalid Travel Date**



| \*\*Field\*\*       | \*\*Description\*\*                   |

| --------------- | --------------------------------- |

| Test Case ID    | TC\_TBP\_Date\_02                    |

| Test Case Title | Verify past date selection        |

| Module Name     | Date Validation                   |

| Preconditions   | Search page open                  |

| Test Steps      | 1. Select past date               |

|                 | 2. Click Search                   |

| Test Data       | Date: Past date                   |

| Expected Result | Error message should be displayed |

| Actual Result   | Error message displayed           |

| Status          | Pass                              |

| Remarks         | Date validation working           |





#### **Test Case 3: Booking Without Login**



| \*\*Field\*\*       | \*\*Description\*\*                         |

| --------------- | --------------------------------------- |

| Test Case ID    | TC\_TBP\_Book\_03                          |

| Test Case Title | Verify booking without login            |

| Module Name     | Booking                                 |

| Preconditions   | User not logged in                      |

| Test Steps      | 1. Select flight                        |

|                 | 2. Click Book                           |

| Test Data       | N/A                                     |

| Expected Result | User should be redirected to login page |

| Actual Result   | Redirected to login page                |

| Status          | Pass                                    |

| Remarks         | Authentication required                 |







