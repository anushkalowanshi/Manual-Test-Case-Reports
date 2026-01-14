#### **Test Case 1: Add Product to Cart**



| \*\*Field\*\*       | \*\*Description\*\*                  |

| --------------- | -------------------------------- |

| Test Case ID    | TC\_ECOM\_Cart\_01                  |

| Test Case Title | Verify add to cart functionality |

| Module Name     | Cart                             |

| Preconditions   | User must be logged in           |

| Test Steps      | 1. Select product                |

|                 | 2. Click Add to Cart             |

| Test Data       | Product: Mobile                  |

| Expected Result | Product added to cart            |

| Actual Result   | Product added successfully       |

| Status          | Pass                             |

| Remarks         | Cart updated correctly           |





#### **Test Case 2: Remove Product from Cart**



| \*\*Field\*\*       | \*\*Description\*\*           |

| --------------- | ------------------------- |

| Test Case ID    | TC\_ECOM\_Cart\_02           |

| Test Case Title | Verify remove from cart   |

| Module Name     | Cart                      |

| Preconditions   | Cart must contain product |

| Test Steps      | 1. Open cart              |

|                 | 2. Click Remove           |

| Test Data       | Product: Mobile           |

| Expected Result | Product removed from cart |

| Actual Result   | Product removed           |

| Status          | Pass                      |

| Remarks         | Remove function works     |





#### **Test Case 3: Checkout Without Address**



| \*\*Field\*\*       | \*\*Description\*\*                   |

| --------------- | --------------------------------- |

| Test Case ID    | TC\_ECOM\_Checkout\_03               |

| Test Case Title | Verify checkout without address   |

| Module Name     | Checkout                          |

| Preconditions   | Product in cart                   |

| Test Steps      | 1. Click Checkout                 |

|                 | 2. Skip address                   |

| Test Data       | Address: blank                    |

| Expected Result | Error message should be displayed |

| Actual Result   | Error message displayed           |

| Status          | Pass                              |

| Remarks         | Address validation working        |



