# passwordchecker

Fun little project that uses an API.

Program checks password locally instead of sending to the web server by using SHA1 algorithm to hash the password
then provides only the first 5 char of the hashed value to be used to request API data.

Program downloads the requested data that matches the first 5 char of the hashed value.
It then loops through the data to check for matches with the rest of the hash value and prints the number of times
password was leaked.
