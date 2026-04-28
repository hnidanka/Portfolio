# Test Suite - Cart
---
# Test Case TC-21

**id:** TC-21
**Title:** Add a single product to the cart
**Priority:** `High`  
**Test Data:** 
* Added product: ADIDAS ORIGINAL



### Preconditions
1. Open: https://rahulshettyacademy.com/client/#/dashboard/dash
2. User must already be logged in the system


### Steps:
Step| Action | Expected result |
| :--- | :--- | :--- |
| 1. | Ensure you can see the 'Home page' | 'Home page' is visible |
| 2. | Locate the product's card you intent to add to the cart (E.g. 'ADIDAS ORIGINAL') and click the 'Add to cart' button | The product is added  to the cart. Message regarding successfully added product is displayed in the right bottom corner. The cart badge counter in the navigation bar updates to '1' |
| 3. | Click on the 'Cart' section in the navigation navbar | User is redirected to the 'Cart' page |
| 4. | Verify whether the added product is present in the cart | The cart list includes the correct product (E.g. 'ADIDAS ORIGINAL') |
| 5. | Verify the added product details in the cart | The product's name, price and image match the selected item |

---

# Test Case TC-22

**id:** TC-22
**Title:** Add two different products to the cart
**Priority:** `High`  
**Test Data:** 
* Added product: ADIDAS ORIGINAL
* Added product: ZARA COAT 3




### Preconditions
1. Open: https://rahulshettyacademy.com/client/#/dashboard/dash
2. User must already be logged in the system
3. Executed TC-21


### Steps:
Step| Action | Expected result |
| :--- | :--- | :--- |
| 1. | Click on the 'Cart' section in the navigation navbar | User is redirected to the 'Cart page'. Cart list is visible and already includes 1 product |
| 2. | Click on the 'Home' section in the navigation navbar | User is redirected to the 'Home page'. Products list is visible below the navigation navbar |
| 3. | Locate another product's cart (E.g. 'ZARA COAT 3') and click the 'Add to cart' button | The product is added  to the cart. Message regarding successfully added product is displayed in the right bottom corner. The cart badge counter in the navigation bar updates to '2' |
| 4. | Click on the 'Cart' section in the navigation navbar | User is redirected to the 'Cart' page |
| 5. | Verify that the cart list includes 2 items and the newly added product is present | The cart contains exactly 2 items. Both products ('ADIDAS ORIGINAL' and 'ZARA COAT 3') are visible in the list |
| 6. | Verify products' details in the cart | Each product's name, price, and image match the selected items |

---

# Test Case TC-23

**id:** TC-23
**Title:** Add two of the same products to the cart
**Priority:** `High`  
**Test Data:** 
* Added products: ADIDAS ORIGINAL



### Preconditions
1. Open: https://rahulshettyacademy.com/client/#/dashboard/dash
2. User must already be logged in the system
3. Executed TC-21


### Steps:
Step| Action | Expected result |
| :--- | :--- | :--- |
| 1. | Click on the 'Cart' section in the navigation navbar | User is redirected to the 'Cart page'. Cart list is visible and already includes 1 product |
| 2. | Click on the 'Home' section in the navigation navbar | User is redirected to the 'Home page'. Products list is visible below the navigation navbar |
| 3. | Locate the same product's cart that is already added to the cart (E.g. 'ADIDAS ORIGINAL') and click the 'Add to cart' button | The product is added  to the cart. Message regarding successfully added product is displayed in the right bottom corner. The cart badge counter in the navigation bar updates to '2' |
| 4. | Click on the 'Cart' section in the navigation navbar | User is redirected to the 'Cart' page |
| 5. | Verify the product entry in the cart list | There is only one row for 'ADIDAS ORIGINAL', but the Quantity field displays '2' |
| 6. | Verify the added products' details in the cart | The products' name, price and image match the selected items |

