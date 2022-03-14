# passwordchecker

Fun little project that uses an Pwned Passwords web API.

Program checks password locally instead of sending to the web server by using SHA1 algorithm to hash the password
then provides only the first 5 char of the hashed value to be used to request API data.

Program downloads the requested data that matches the first 5 char of the hashed value.
It then loops through the data locally to check for matches with the rest of the hash value and prints the number of times
password was leaked.

Sample output shown below
(Input password used in sample: HelloWorld!, HelloWorld!123@##, password)

![Screen Shot 2022-03-14 at 3 06 33 PM](https://user-images.githubusercontent.com/39870122/158252486-1c21ffda-31e8-4ee2-b2aa-e8704077ec00.png)
