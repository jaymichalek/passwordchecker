# passwordchecker

Fun little project that uses an Pwned Passwords web API.

Program checks password locally instead of sending to the web server by using SHA1 algorithm to hash the password
then provides only the first 5 char of the hashed value to be used to request API data.

Program downloads the requested data that matches the first 5 char of the hashed value.
It then loops through the data locally to check for matches with the rest of the hash value and prints the number of times
password was leaked.

Sample output shown below
(Input password used in sample: password and HelloWorld!)

![Screen Shot 2022-03-14 at 3 09 38 PM](https://user-images.githubusercontent.com/39870122/158252961-d9a5d7bc-7f4f-484f-9f3c-b481c7627b0e.png)

