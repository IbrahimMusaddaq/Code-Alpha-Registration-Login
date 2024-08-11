Explanation of the Code
registerUser Function:

Prompts the user for a username and password.
Creates a text file named after the username and stores the credentials in the file.
loginUser Function:

Prompts the user for their username and password.
Opens the file associated with the username and checks if the entered credentials match those stored in the file.
Returns true if the login is successful, otherwise returns false.
main Function:

Presents a menu with options to register or log in.
Calls the appropriate function based on the user’s choice.
If the login fails, the user is given an option to retry.
