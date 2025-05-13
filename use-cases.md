# Use Case: Login to the system

## Users
- End user

## Trigger
- The user clicks the "Login" button on the homepage.

## Preconditions
- The user must have an account on the website.

## Postconditions
- The user successfully logs into the system and is redirected to the homepage.

## Basic Flow
1. The user opens the login page.
2. The user enters their username and password.
3. The user clicks the "Login" button.
4. If the credentials are correct, the user is redirected to the homepage.

## Exceptional Flow
- If the credentials are incorrect, an error message "Invalid username or password" is displayed.

# Use Case: Register a new user

## Users
- New user

## Trigger
- The user clicks the "Register" button on the homepage.

## Preconditions
- The user does not have an existing account.

## Postconditions
- A new user account is created, and the user is logged in and redirected to the homepage.

## Basic Flow
1. The user clicks on "Register" from the homepage.
2. The user fills out the registration form with their details (username, email, password).
3. The user submits the registration form.
4. If the data is valid, the user is registered and logged in automatically.

## Exceptional Flow
- If the user submits invalid or incomplete data, an error message is displayed explaining what needs to be corrected.

# Use Case: View Profile

## Users
- Logged-in user

## Trigger
- The user clicks on their profile icon or "Profile" in the navigation menu.

## Preconditions
- The user must be logged in.

## Postconditions
- The user views their profile information.

## Basic Flow
1. The user clicks on the "Profile" option from the navigation menu.
2. The user’s profile page is displayed with their personal information.

## Exceptional Flow
- If the user is not logged in, they are redirected to the login page.
