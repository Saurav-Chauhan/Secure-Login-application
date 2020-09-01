# Secure-Login-application
Secure Login application which include securing Activities and all secure coding practices in Android.

✓ Register a user by providing user profile such as mobile no, email id, organization and other user relevant information.

✓ Fetch the user credentials from a server to authenticate the user with username and password before providing access to the user.

✓ Use SSL for communication between the client and server
✓ On successful login, go to the next screen. On failing login, alert user by toast
✓ If the user enters wrong credentials for three times, then terminate the applicationNext screen should display user profile
✓ No other application in the device should be able to start the internal activities except the login screen (use exported=fasle for all internal activities)
✓ Only use explicit intents to call activities within the application
✓ Sanitize all data inputedby the user before using it in the application
