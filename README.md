# check_your_password
# This is CLI(Command Line Interface) Application
This application uses API from https://haveibeenpwned.com/ and tells whether your password has ever been hacked but in a more secured way.
You don't need to send your password over the internet because someone may hack it in between.
This application converts your password into hash code using hash function and sends first five characters of that code to the API and the server returns all hash code password to your system.
A for loop then matches your hashed password in the hashed password data you have on your system.
