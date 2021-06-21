# Sum of letters
*If every letter in English alphabet has a number from 1 to 26, what would be the sum of all letters in your name?*

When I saw "every letter in English alphabet has a number", I immediately thought of the ASCII table. Because there all English letters are already linked alphabetically with numbers. So I don't have to care about that anymore.
Since all lowercase letters in the ASCII table have a value from 97 to 122, I only have to subtract 96 from that to get values 1 to 26. All other values can be skipped.
I decided to use the lower case letters, otherwise there would be problems with the German letter "ß". This would be converted to "SS" in capital letters and therefore not be skipped. Thus, in this case, the sum would be wrong if capitalized.

## How it works
Since I have not yet worked with testing libraries, I created my own manually.
- The file "sumOfLetters.js"  contains the actual application.
- The file "sumOfLetters.test.js" tests various units and exports the results
- The file "workingWithDom.js" receives the test results and updates the DOM of "index.html"

To see the result, just open the file at the following link:
https://www.cykriz.de/sumOfLetters

## Feedback
I found the task to be rather easy, as the ASCII table already assigns a number to each English letter and you can easily filter out all non-English letters.
Since I have not yet worked with testing libraries, the unit tests were the most challenging for me.
