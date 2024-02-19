# console-based-social-media-application-implemented-in-C-

#1. Overview:

The provided code is a simple console-based social media application
implemented in C++. It includes functionality for user registration,
login, creating posts, and viewing posts. Users can sign up with a
unique username and password, log in, create posts, and view posts
either from all users or specific individuals.

#2. Code Structure:

User and Post Structures:

User structure contains information about a user, including a
username and password.
Post structure represents a post, consisting of an author's username
and the post content.
Global Variables:

std::vector<User> users: Stores user information.
std::vector<Post> posts: Stores posts made by users.
User* currentUser: Represents the currently logged-in user.
Functions:

createUser: Adds a new user to the users vector.
findUser: Searches for a user in the users vector based on the
provided username.
loginUser: Validates user credentials and logs in the user if they exist.
createPost: Allows the currently logged-in user to create a new post.
view Posts:
Provides options to view posts, either all posts or individual posts of
a specific user.
Main Function:

Implements the main menu with options for sign-up, login, post
creation, post viewing, and exit.
Uses a loop to repeatedly display the menu until the user chooses to
exit.
#3. User Interaction:

Users interact with the application through a console-based menu.
The program prompts users for input, such as usernames, passwords,
post content, and menu choices.
The user has the option to sign up, log in, create posts, and view
posts.
#4. Improvements and Suggestions:

Security:

Passwords are stored in plain text. Consider implementing a secure
password storage mechanism, such as hashing.
Error Handling:

Enhance error handling, providing more informative messages for
invalid inputs or failed operations.
Code Modularity:

Consider breaking down the main function into smaller, more
modular functions to improve code readability and maintainability.
Memory Management:

The code uses pointers (User* currentUser) for user management.
Consider using safer alternatives, such as smart pointers or
references.
#5. Conclusion:
The provided code offers a basic framework for a social media
application. It successfully manages user registration, login, post
creation, and viewing. Enhancements in security, error handling,
code modularity, and memory management could be considered for
future improvements.
This report provides an overview of the code's structure,
functionality, and suggestions for enhancements. If you have specific
questions or areas you'd like to focus on, feel free to ask for more
detailed information. questions or areas you'd like to focus on, feel
free to ask for more detailed information.
