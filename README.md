# Bugs
Below are some bugs that I wrote.


----------------------------
# Login is not working properly

**Description:**
When trying to login with correct credentials, nothing happens.
The user is not logged in and no error message is displayed.

**Steps to Reproduce:**
1. Go to www.website.com/login
2. Add a correct user/pass
3. Press Login button

**Expected Result:**
User should be able to login and is taken to his profile page.

**Actual Result:**
User is not logged and no error appears.

**Test Data:**
User: Sebastian & Pass: 1234


-----------------------------

# Change password is not working properly

**Description:**
After succesfully loging in with correct credentials, when trying to change password by clicking on the "Change Password" button in the "Profile" menu, nothing happens.

**Steps to Reproduce:**
1. Go to www.website.com/login
2. Enter the correct credentials
3. Press "Login" button
4. Go to "Profile" menu
5. Press "Change Password" button

**Expected Result:**
User should be redirected to the "Change Password" page.

**Actual Result:**
User is not redirected to the "Change Password" page and remains in the "Profile" page.

**Test Data:**
User: RaduSebastian & Pass: 1234
