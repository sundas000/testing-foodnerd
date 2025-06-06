# Login Module – Test Cases (Foodnerd Electron)

| Test Case ID | Module       | Test Case Description                                         | Expected Result                                                  | Priority | Execution Status | Notes                     |
|--------------|--------------|----------------------------------------------------------------|-------------------------------------------------------------------|----------|------------------|---------------------------|
| TC_LOGIN_001 | Login Page   | Verify that the Email field accepts valid email format         | Email is accepted if it follows format (e.g., user@mail.com)      | High     | Pass             |                           |
| TC_LOGIN_002 | Login Page   | Verify that the Email field shows an error for invalid format  | User sees validation message for invalid email format             | High     | Pass             |                           |
| TC_LOGIN_003 | Login Page   | Verify that the Password field accepts input                   | User is able to enter password                                    | High     | Pass             |                           |
| TC_LOGIN_004 | Login Page   | Verify Login fails when email or password is incorrect         | Error message appears: "Invalid credentials"                      | High     | Pass             |                           |
| TC_LOGIN_005 | Login Page   | Verify Login is successful with correct email & password       | User is redirected to the dashboard                               | High     | Pass             |                           |
| TC_LOGIN_006 | Login Page   | Verify the "Remember Me" checkbox retains login info on restart| Email/password auto-filled on relaunch if checkbox was selected  | Medium   | Pass             |                           |
| TC_LOGIN_007 | Login Page   | Verify Login fails with blank fields                           | Validation messages shown: "Email is required", "Password is required" | High | Pass             |                           |
| TC_LOGIN_008 | Login Page   | Verify tab order among fields (Email → Password → Remember Me → Login) | Cursor moves in logical tab order                      | Low      | Pass             |                           |
| TC_LOGIN_009 | Login Page   | Verify that pressing "Enter" key submits the login form        | Login is attempted when pressing Enter in the Password field      | Medium   | Pass             |                           |
| TC_LOGIN_010 | Login Page   | Verify masking of Password field                               | Password input is hidden with dots or asterisks                   | High     | Pass             |                           |
