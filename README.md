Project Overview: 
This project is a simple login interface built with SwiftUI for iOS. It demonstrates basic authentication logic within the app by comparing user-inputted credentials with predefined values. The app displays feedback messages to indicate a successful or failed login attempt.

Features

Username Input Field: Allows the user to enter a username.
Password Input Field: A secure input field that hides the text for privacy.
Login Button: Triggers the login validation function.
Feedback Message: Displays success or failure messages based on login attempts.
Technology Used

Swift: The programming language used.
SwiftUI: Apple's declarative UI framework.


Code Structure
ContentView
The main SwiftUI view, ContentView, is composed of:

@State properties to manage the state of the username, password, and feedback message.
TextField and SecureField for username and password input, respectively.
A Button that triggers the login function to check credentials.
A Text view to display a success or failure message.


login() Function

The login function compares the entered username and password against hardcoded values ("admin" and "password"). If the credentials match, a success message is shown; otherwise, a failure message is displayed.

Usage


Open the Project: Clone the repository and open it in Xcode.
Run the App: Build and run the app on a simulator or a physical device.
Enter Credentials: Type in "admin" as the username and "password" as the password to successfully log in.
Feedback: If the credentials are correct, the message will show "Login successful"; otherwise, it will display "Invalid credentials
