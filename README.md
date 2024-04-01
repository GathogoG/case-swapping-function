Swap Case
This Node.js script, swapCase.js, provides a functionality to swap the case of each alphabetic character in a given string.

Usage
Ensure you have Node.js installed on your system.

Clone or download the swapCase.js file.

Open a terminal window.

Navigate to the directory containing swapCase.js.

Run the script by executing the following command:

Copy code
node swapCase.js
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
$ node swapCase.js
Enter a string: Hello World
Swapped case: hELLO wORLD
This script provides a convenient way to swap the case of characters in a given string.



