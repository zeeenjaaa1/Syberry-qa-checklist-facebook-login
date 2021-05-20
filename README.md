# Checklist for testing facebook.com

# **Smoke testing**

***for Login Page*** :

1. Enter the correct login and correct password and clicking on the 'Login' button. 
2. Enter the correct login and correct password and pressing Enter key.
3. Enter an incorrect username and incorrect password.
4. Check if the password is in masked form when typed in the password field.

***for Sign Up Page :***

1. Register a new user by entering correct data. 
2. Inability to register a new user by entering incorrect data.
3. РЎheck the required fields in the registration form

***for Forgot Password Page:***

1. Successful authorization in the system after changing the password
2. Password less than 6 characters will not be registered

# Critical path testing

***for Login Page*** :

1. Verify that as soon as the login page opens, by default the cursor should remain on the username textbox.
2. Verify that the user is able to navigate or access the different controls by pressing the 'Tab' key on the keyboard.
3. Verify that all the labels and controls including text-boxes, buttons, and links are present on the Login page
4. Enter an incorrect username and correct password.
5. Enter the correct username and incorrect password.
6. Verify that the validation message gets displayed in case the user leaves the username or password field as blank.
7. Limit on the total number of unsuccessful login attempts
8. Hide / show password in input field

***for Sign Up Page :***

1. Registration of a user with an existing login/phone number/name-surname
2. User registration with existing password
3. Password less than 6 characters will not be registered
4. Verify that the validation message is displayed in case the user leaves a required field empty or with incorrect data.
5. Verify that the validation message is displayed when you enter an invalid date of birth.
6. Verify that the user is able to navigate or access the different controls by pressing the 'Tab' key on the keyboard
7. Verify that all the labels and controls including text-boxes, buttons, and links are present on the Sign Up page

***for Forgot Password Page:***

1. Verify that if you enter an incorrect email or phone number, the password will not be changed
2. Verify that all the labels and controls including text-boxes, buttons, and links are present on the Forgot Password page
3. Verify that when you try to enter the wrong code (it comes to mail or SMS), an error message appears
4. Password less than 6 characters will not be registered
5. Enter password without numbers
6. Enter your name in the password field
7. Write password in capital letters only
8. Write password in lowercase letters only
9. Hide / show password in input field

# Extended testing

***for Login Page:***

1. Check if the password can be copy-pasted or not.
2. Enter the correct login. The password is written in capital letters.
3. Enter the correct password. The login is written in capital letters.
4. The login and the password are written in lowercase letters
5. Leave an empty field login. Field password - correct data
6. Leave the password field empty, the login field with the correct data
7. Enter the correct password in the login field, and enter the correct login in the password field.
8. Enter the correct login, starting with several spaces, and the correct password 
9. Enter the correct login, followed by several spaces, and the correct password 
10. Leave both fields blank
11. Enter the login "ksjdksbdshdoueywfgjwevflwjeyfvowyecsydcvsldc" (not existing in the database), leave the password field empty

***for Sign Up Page :***

1. Check the limit on the length of the fields name / surname / email / password when registering
2. User registration with a password containing spaces or consisting of only spaces
3. Registration of a user with a login containing spaces or consisting of only spaces
4. Register a new user with the name "newuser" and the password "newuser" (full match).
5. Enter special characters in the name/ surname/password/email fields
6. Do not indicate gender

***for Forgot Password Page:***

1. Enter a password consisting of spaces
2. Create a password with as many characters as possible
3. Enter in the password field a complex sequence of characters like '~! @ # $% ^ & * ()?>,. / \ <] [/ * ’
4. Creating a password in Cyrillic
5. Enter a password less than 6 characters
6. Enter the password, starting with several spaces
7. Enter the password, followed by several spaces
8. Enter your name in the password field
