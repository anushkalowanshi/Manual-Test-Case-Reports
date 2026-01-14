#### **Test Case 1: Valid Login**



| \*\*Field\*\*       | \*\*Description\*\*             |

| --------------- | --------------------------- |

| Test Case ID    | TC\_BANK\_Login\_01            |

| Test Case Title | Verify banking login        |

| Module Name     | Login                       |

| Preconditions   | User must be registered     |

| Test Steps      | 1. Open login page          |

|                 | 2. Enter credentials        |

|                 | 3. Click Login              |

| Test Data       | Username: user01            |

|                 | Password: pass@123          |

| Expected Result | User logged in successfully |

| Actual Result   | Login successful            |

| Status          | Pass                        |

| Remarks         | Secure login working        |





#### **Test Case 2: Fund Transfer**



| \*\*Field\*\*       | \*\*Description\*\*                      |

| --------------- | ------------------------------------ |

| Test Case ID    | TC\_BANK\_Transfer\_02                  |

| Test Case Title | Verify fund transfer                 |

| Module Name     | Fund Transfer                        |

| Preconditions   | User logged in and balance available |

| Test Steps      | 1. Enter beneficiary                 |

|                 | 2. Enter amount                      |

|                 | 3. Click Transfer                    |

| Test Data       | Amount: 5000                         |

| Expected Result | Amount transferred successfully      |

| Actual Result   | Transfer successful                  |

| Status          | Pass                                 |

| Remarks         | Transaction successful               |

#### 

#### **Test Case 3: Invalid Amount Transfer**



| \*\*Field\*\*       | \*\*Description\*\*                           |

| --------------- | ----------------------------------------- |

| Test Case ID    | TC\_BANK\_Transfer\_03                       |

| Test Case Title | Verify transfer with insufficient balance |

| Module Name     | Fund Transfer                             |

| Preconditions   | User logged in                            |

| Test Steps      | 1. Enter high amount                      |

|                 | 2. Click Transfer                         |

| Test Data       | Amount: 1,00,000                          |

| Expected Result | Error message shown                       |

| Actual Result   | Error message displayed                   |

| Status          | Pass                                      |

| Remarks         | Balance validation working                |



