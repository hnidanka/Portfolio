# Test Suite - Login
---
# Test Case TC-11

**id:** TC-11
**Title:** Log in to the system (Valid)
**Priority:** `High`  
**Test Data:** 
* Email: anna2001K@gmail.com
* Password: Ann870@K



### Preconditions
1. Open: https://rahulshettyacademy.com/client/#/auth/register
2. User must already be registered in the system


### Steps:
Step| Action | Expected result |
| :--- | :--- | :--- |
| 1. | Ensure you can see the Log in form | Log in page is opened|
| 2. | Fill in the 'Email' field with valid value (E.g. 'anna2001K@gmail.com') | Field 'Email' is populated witha data |
| 3. | Fill in the 'Password' field with valid value ('E.g. 'Ann870@K') | Field 'Password' is populated with a value. Provided value is masked with dots |
| 4. | Click on the 'Login' button | Message regarding successful login is displayed in the right bottom corner. User is logged into the system and redirected to the 'Home page' |
----------

# Test Case TC-12

**id:** TC-12
**Title:** Log in to the system (invalid)
**Priority:** `High`  
**Test Data:** 
* Email - valid: anna2001K@gmail.com
* Password - valid : Ann870@K
* Email - invalid: anna2001@gmail.com
* Password - invalid: Ann70@K
* Email - invalid uppercase: ANNA2001@GMAIL.COM
* Password - invalid uppercase: ANN870@K
*Email - invalid format: anna2001K_at_gmail.com



### Preconditions
1. Open: https://rahulshettyacademy.com/client/#/auth/register
2. User must already be registered in the system

### Steps:
Step| Action | Expected result |
| :--- | :--- | :--- |
| 1. | Ensure you can see the Log in form | Log in page is opened|
| 2. | Fill in the 'Email' field with invalid value (E.g. 'anna2001@gmail.com') | Field 'Email' is populated with invalid value |
| 3. | Fill in the 'Password' field with valid value ('E.g. 'Ann870@K') | Field 'Password' is populated with value. Provided value is masked with dots |
| 4. | Click on the 'Login' button | Message regarding incorrect email or password is displayed in the right bottom corner. User is not logged into the system| 
| 5. | Replace 'Email' field value with valid value (E.g. 'anna2001K@gmail.com') | 'Email field is populated with valid value |
| 6. | Replace ' Password' field with invalid value (E.g. 'Ann70@K') | 'Password' field is populated with invalid value. Provided value remains masked|
| 7. | Click on the 'Login' button | Message regarding incorrect email or password is displayed in the right bottom corner. User is not logged intothe system | 
| 8. | Replace 'Email' field value with invalid value (E.g. 'anna2001@gmail.com') | 'Email' field is populated with invalid value |
| 9. | Click on the 'Login' button | Message regarding incorrect email or password is displayed in the right bottom corner. Uer is not logged in to the system |
| 10. | Modify the 'Password' field by adding a space after the existing characters | 'Password' field is populated with updated value. Provided value remains masked |
| 11. | Click on the 'Login' button | Message regarding incorrect email or password is displayed in the right bottom corner. User is not logged in to the system |
| 12. | Reverse 'Password field with the value provided in the step #3 | 'Password field is populated with a value from step #3. Provided value remains masked |
| 13. | Modify 'Email' field valued by adding a space before the existing characters | 'Email' field is populated with updated value |
| 14. | Click on the 'Login' button | Message regarding incorrect email or password is displayed in the right bottom corner. User is not logged in to the system |
| 15. | Replace 'Email' field value with a valid value using uppercase characters (E.g. 'ANNA2001K@GMAIL.COM') | 'Email' field is populated with a valid  uppercase value |
| 16. | Click on the 'Login' button | Message regarding incorrect email or password is displayed in the right bottom corner. User is not logged in to the system |
| 17. | Reverse 'Email' field value with the value provided in the step #5 | 'Email' field is populated with a valid value |
| 18. | Replace 'Password' field value with a valid value using uppercase characters (E.g. 'ANN870@K') | 'Password field is populated with a valid uppercase value. Provided value remains masked | 
| 19. | Click on the 'Login' button | Message regarding incorrect email or password is displayed in the right bottom corner. User is not logged in to the system |
| 20. | Reverse 'Password' field value with the value provided in the step #3 | 'Password field is populated with a valid value |
| 21. | Fill in the 'Email' field with an invalid format (E.g. 'anna2001K_at_gmail.com') | 'Email' field is populated with invalid format value |
| 22. | Click on the 'Login' button | Message regarding incorrect email  is displayed under 'Email field'. Login button is disabled |
----------

# Test Case TC-13

**id:** TC-13
**Title:** Log in to the system with missing values
**Priority:** `High`  
**Test Data:** 
* Email: anna2001K@gmail.com
* Password: Ann870@K



### Preconditions
1. Open: https://rahulshettyacademy.com/client/#/auth/register
2. User must already be registered in the system


### Steps:
Step| Action | Expected result |
| :--- | :--- | :--- |
| 1. | Ensure you can see the Log in form | Log in page is opened|
| 2. | Fill in the 'Email' field with valid value (E.g. 'anna2001K@gmail.com') | Field 'Email' is populated witha data |
| 3. | The 'Password' field must be empty | Field 'Password' is empty |
| 4. | Click on the 'Login' button | Inline validation message regarding required password is displayed. Login button is disabled. User is not logged into the system |
| 5. | Fill in the 'Password' field with a valid value (E.g. 'Ann870@K') | 'Password field is populated with valid value. Inline password validation message is not displayed |
| 6. | Clear 'Email' field value and leave it empty | 'Email' field value is empty. Inline validation message regarding required email is displayed|
| 7. | Click on the 'Login' button | Button is disabled. User is not logged in to the system. Inline validation message regarding required email remains visible |
| 8. | Clear 'Password" field value and leave it empty | 'Password' field value is empty .Inline validation message regarding required password is displayed |
| 9. | Click on the 'Login' button | 'Login' button is disabled. User is not logged in to the system, Inline messages regarding missing required 'Email' field and 'Password' field values are displayed |
----------

# Test Case TC-14

**id:** TC-14
**Title:** Log in form Accessibility testing
**Priority:** `High`  
**Test Data:** 
* Email: anna2001K@gmail.com
* Password: Ann870@K



### Preconditions
1. Open: https://rahulshettyacademy.com/client/#/auth/register
2. User must already be registered in the system


### Steps:
Step| Action | Expected result |
| :--- | :--- | :--- |
| 1. | Ensure you can see the Log in form | Log in page is opened|
| 2. | Fill in the 'Email' field with valid value (E.g. 'anna2001K@gmail.com') | Field 'Email' is populated witha data |
| 3. | Press the 'Tab' key | Ensure input focus is moved to the 'Password' field |
| 4. | Fill in the 'Password' field with valida data (E.g. 'Ann870@K') | 'Password' field is populated with a valid data. Input value is masked with dots |
| 5. | Press the 'Enter' key | User is successfully legged into the system and redirected to the 'Home page'. Message regarding successfull login is displayed in the right bottom corner |
----------