# Test Suite - Registration
---
# Test Case TC-01

**id:** TC-01
**Title:** Register a new user (All fields)
**Priority:** `High`  
**Test Data:** 
* First name: Anna
* Last Name: Kowalska
* Email: anna2001K@gmail.com
* Phone number: 7305629530
* Occupation: Engineer
* Gender: Female
* Password: Ann870@K
* Confirm Password: Ann870@K
* Age: Older than 18 years old


### Preconditions
1. Open: https://rahulshettyacademy.com/client/#/auth/register


### Steps:
Step| Action | Expected result |
| :--- | :--- | :--- |
| 1. | Ensure you can see the register form | Register page is opened|
| 2. | Fill in the 'First Name' field with valid value (E.g. 'Anna ') | Field 'First Name' is populated witha value |
| 3. | Fill in the 'Last Name' field with valid value (E.g. 'Kowalska' ) | Field 'Last Name' is populated with a value |
| 4. | Fill in the 'Email' field with a valid value (E.g. 'anna2001K@gmail.com') | Field 'Email' is populated with a value |
| 5. | Fill in the 'Phone number' field with a valid value (E.g. '7305629530') | Field 'Phone number' is populated with a value |
| 6. | Click on the 'Occupation' dropdown and select available option from the list (E.g. 'Engineer')| Selected option is displayed in the 'Occupation' field |
| 7. | Select any available radio button option in the 'Gender' section (E.g. 'Female') | Radio button is selected |
| 8. | Fill in the 'Password' field with a valid value (E.g. 'Ann870@K') | Field 'Password' is populated and enetered value is masked with a dots |
| 9. | Fill in the 'Confirm Password' field with the same value from previous step (E.g. 'Ann870@K') | Field 'Confirm Password' is populated and entered value is masked with a dots |
| 10. | Select 'I am 18 year or Older' checkbox | Checkbox is selected |
| 11. | Click 'Register' button | The registration form is accepted and closed; 'Account Created Successfully' block is displayed; 'Login' button is displayed in the active state .|
| 12. | Verify user is created and is able to login into the system: Click 'Login' button | 'Login' form is displayed |
| 13. | Fill in the 'Email' field with value provided in step #4 | Field 'Email' is populated |
| 14. | Fill in the 'Password' field with a value provided in step #8 | Field 'Password' is populated |
| 15. | Click 'Login' button | User is successfully logged into the system; "Login successfully mesage' is displayed; User is redirected to the main Page |

----------

# Test Case TC-02

**id:** TC-02
**Title:** Register a new user only with required data
**Priority:** `High`  
**Test Data:** 
* First name: Maria
* Last Name: Johnos
* Email: maria20728H@gmail.com
* Phone number: 7305629349
* Password: haT67!jhh
* Confirm Password: haT67!jhh
* Age: Older than 18 years old


### Preconditions
1. Open: https://rahulshettyacademy.com/client/#/auth/register


### Steps:
Step| Action | Expected result |
| :--- | :--- | :--- |
| 1. | Ensure you can see the register form | Register page is opened|
| 2. | Fill in the 'First Name' field with valid value (E.g. 'Maria ') | Field 'First Name' is populated witha value |
| 3. | Fill in the 'Last Name' field with valid value (E.g. 'Johnos' ) | Field 'Last Name' is populated with a value |
| 4. | Fill in the 'Email' field with a valid value (E.g. 'maria20728H@gmail.com') | Field 'Email' is populated with a value |
| 5. | Fill in the 'Phone number' field with a valid value (E.g. '7305629349') | Field 'Phone number' is populated with a value |
| 6. | Fill in the 'Password' field with a valid value (E.g. 'haT67!jhh') | Field 'Password' is populated and enetered value is masked with a dots |
| 7. | Fill in the 'Confirm Password' field with the same value from previous step (E.g. 'haT67!jhh') | Field 'Confirm Password' is populated and entered value is masked with a dots |
| 8. | Select 'I am 18 year or Older' checkbox | Checkbox is selected |
| 9. | Click 'Register' button | The registration form is accepted and closed; 'Account Created Successfully' block is displayed; 'Login' button is displayed in the active state .|
| 10. | Verify user is created and is able to login into the system: Click 'Login' button | 'Login' form is displayed |
| 11. | Fill in the 'Email' field with value provided in step #4 | Field 'Email' is populated |
| 12. | Fill in the 'Password' field with a value provided in step #5 | Field 'Password' is populated |
| 13. | Click 'Login' button | User is successfully logged into the system; "Login successfully mesage' is displayed; User is redirected to the main Page |


----------

# Test Case TC-03

**id:** TC-03
**Title:** Register a new user with missing required fields
**Priority:** `High`  
**Test Data:** 
* First name: Maria
* Last Name: Johnos
* Email: maria20728H@gmail.com
* Phone number: 7305629349
* Password: haT67!jhh
* Confirm Password: haT67!jhh
* Age: Older than 18 years old


### Preconditions
1. Open: https://rahulshettyacademy.com/client/#/auth/register


### Steps:
Step| Action | Expected result |
| :--- | :--- | :--- |
| 1. | Ensure you can see the register form | Register page is opened|
| 2. | Fill in the 'First Name' field with valid value (E.g. 'Maria ') | Field 'First Name' is populated witha value |
| 3. | Fill in the 'Email' field with a valid value (E.g. 'maria20728H@gmail.com') | Field 'Email' is populated with a value |
| 4. | Fill in the 'Phone number' field with a valid value (E.g. '7305629349') | Field 'Phone number' is populated with a value |
| 5. | Fill in the 'Password' field with a valid value (E.g. 'haT67!jhh') | Field 'Password' is populated and enetered value is masked with a dots |
| 6. | Fill in the 'Confirm Password' field with the same value from previous step (E.g. 'haT67!jhh') | Field 'Confirm Password' is populated and entered value is masked with a dots |
| 7. | Select 'I am 18 year or Older' checkbox | Checkbox is selected |
| 8. | Click 'Register' button | The registration form is not accepted; 'Last Name is required' message is displayed beneath the 'Last Name field; 'Register' button isn't active; Request to register a new user isn't sent' |
| 9. | Fill in the 'Last Name' field with valid value (E.g. 'Johnos' ) | Field 'Last Name' is populated with a value; Error message regarding missing value is not displayed |
| 10. | Delete the value from 'First Name' field | Field 'First name' is empty; Error message regarding missing 'First Name' value is displayed under the field |
| 11. |Click 'Register' button | The registration form is not accepted; 'Last Name is required' message is displayed beneath the 'Last Name field; 'Register' button isn't active; Request to register a new user isn't sent' |
| 12. | Fill in the 'First Name' field with the value prowided in step#2 | 'First Name' field is populated with a value; Error message regarding missing value is not displayed |
| 13. | Delete the value from 'Email' field | Field 'Email' is empty; Error message regarding missing 'Email' value is displayed |
| 14. | Click on the 'Register' button | The registration form is not accepted; Error regarding missing 'Email' value is displayed under the field; 'Register' button isn't active;  Request to register a new user was not sent |
| 15. | Fill in the 'Email' field with the value provided in step#3 | Field 'Email' is populated with a value; Error message regarding missing value is not displayed |
| 16. | Delete the value from 'Phone number' field | 'Phone number' field is empty; Error regarding missing 'Phone number' value is displayed under the field |
| 17. | Click on the 'Register' button | Form is not accepted; Error message regarding missing value for 'Email' field is displayed; 'Register' button is not active; Request to register a new user was not sent |
| 18. | Fill in the 'Phone number' field with the value provided in step#4 | 'Phone number' field is populated; Error message regarding missing value is not displayed |
| 19. | Delete the value from 'Password' field | 'Password' field is empty; Error message regarding missing 'Password' value is displayed; Mismatch Error between 'Password' and 'Confirm password' values is displayed under the 'Confirm Password' field |
| 20. | Click on the 'Register' button | The regastration form is not accepted; Errors regarding missing 'Password' value and Mismath error are displayed; 'Register' button is not active; Request to register a new user was not sent |
| 21. | Fll in the 'Password' value with the value provided in step#5 | 'Password' field is populated; Error messages regarding missing value and mismatch values are not displayed |
| 12. | Delete the value from 'Confirm Password' field | 'Confirm Password' field is empty; Error message regarding missing 'Confirm Password' value is displayed;  |
| 20. | Click on the 'Register' button | The regastration form is not accepted; Errors regarding missing 'Confirm Password' value; 'Register' button is not active; Request to register a new user was not sent |
| 21. | Fll in the 'Confirm Password' value with the value provided in step#6 | 'Confirm Password' field is populated; Error message regarding missing value is not displayed |
| 22. | Unselect 'I am 18 year or Older' checkbox | checkbox is not selected; error message regarding not checked field is displayed; |
| 23. | Click on the 'Register' button | Form is not accepted; Message regarding not checked checkbox is displayed; 'Register' button is not active; Request to register a new user was not sent |



----------

# Test Case TC-04

**id:** TC-04
**Title:** Register a new user with invalid phone number
**Priority:** `High`  
**Test Data:** 
* First name: Maria
* Last Name: Johnos
* Email: maria20728H@gmail.com
* Phone number: 730562
* Password: haT67!jhh
* Confirm Password: haT67!jhh
* Age: Older than 18 years old


### Preconditions
1. Open: https://rahulshettyacademy.com/client/#/auth/register


### Steps:
Step| Action | Expected result |
| :--- | :--- | :--- |
| 1. | Ensure you can see the register form | Register page is opened|
| 2. | Fill in the 'First Name' field with valid value (E.g. 'Maria ') | Field 'First Name' is populated witha value |
| 3. | Fill in the 'Last Name' field with valid value (E.g. 'Johnos' ) | Field 'Last Name' is populated with a value |
| 4. | Fill in the 'Email' field with a valid value (E.g. 'maria20728H@gmail.com') | Field 'Email' is populated with a value |
| 5. | Fill in the 'Phone number' field with a invalid value (E.g. '730562') | Field 'Phone number' is populated with a value; Error message 'Phone Number must be 10 digit' is displayed|
| 6. | Fill in the 'Password' field with a valid value (E.g. 'haT67!jhh') | Field 'Password' is populated and enetered value is masked with a dots |
| 7. | Fill in the 'Confirm Password' field with the same value from previous step (E.g. 'haT67!jhh') | Field 'Confirm Password' is populated and entered value is masked with a dots |
| 8. | Select 'I am 18 year or Older' checkbox | Checkbox is selected |
| 9. | Click 'Register' button | Register form is not accepted; Error message 'Phone Number must be 10 digit' is displayed under 'Phone number' field; 'Register' button is not active; Request ti register user isn't sent |


----------

# Test Case TC-05

**id:** TC-05
**Title:** Register a new user with the Email value that is already used by another regirested user
**Priority:** `High`  
**Test Data:** 
* First name: Maria
* Last Name: Johnos
* Email: maria20728H@gmail.com
* Phone number: 7305629349
* Password: haT67!jhh
* Confirm Password: haT67!jhh
* Age: Older than 18 years old


### Preconditions
1. User is already registered


### Steps:
Step| Action | Expected result |
| :--- | :--- | :--- |
| 1. | Ensure you can see the register form | Register page is opened|
| 2. | Fill in the 'First Name' field with valid value (E.g. 'Maria ') | Field 'First Name' is populated witha value |
| 3. | Fill in the 'Last Name' field with valid value (E.g. 'Johnos' ) | Field 'Last Name' is populated with a value |
| 4. | Fill in the 'Email' field with the same value that is already assigned to another registered user (E.g. 'maria20728H@gmail.com') | Field 'Email' is populated with a value |
| 5. | Fill in the 'Phone number' field with invalid value (E.g. '7305629349') | Field 'Phone number' is populated with a value; Error message 'Phone Number must be 10 digit' is displayed|
| 6. | Fill in the 'Password' field with a valid value (E.g. 'haT67!jhh') | Field 'Password' is populated and enetered value is masked with a dots |
| 7. | Fill in the 'Confirm Password' field with the same value from previous step (E.g. 'haT67!jhh') | Field 'Confirm Password' is populated and entered value is masked with a dots |
| 8. | Select 'I am 18 year or Older' checkbox | Checkbox is selected |
| 9. | Click 'Register' button | Register form is not accepted; Error Message regarding dublicate e-mail is displayed; Request responded with status 400 'Bad request'|