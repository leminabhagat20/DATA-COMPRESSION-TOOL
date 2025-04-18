# DATA-COMPRESSION-TOOL

COMPANY: CODTECH IT SOLUTIONS

NAME: LEMINA BHAGAT

INTERN ID: CT04WE100

DOMAIN: C PROGRAMMING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

#DESCRIPTION:
The C program performs a basic but highly effective Run-Length Encoding (RLE) compression on a user-input string. Run-Length Encoding is a simple data compression technique that reduces the size of strings by replacing consecutive repeating characters with a single character followed by the number of times it repeats. For example, if the input is “aaabbccccd”, the RLE output becomes “a3b2c4d1”. This technique is especially useful when the input contains a lot of repetition, making the data smaller and more efficient for storage or transmission. The purpose of this program is to introduce beginners to both the concept of data compression and the implementation of string manipulation in C using basic programming logic.

At the core of the program is a function that processes the input string character by character. It begins by prompting the user to enter a word or string they want to compress. Once the input is taken using standard input functions, the program then begins analyzing it from left to right. The idea is to check each character and count how many times it appears in sequence. For every unique character or group of repeated characters, the program keeps track of how many times the character appears in a row and then prints it once followed by the count. This logic continues until the end of the string, ensuring that every character and its frequency are accounted for.

Internally, a loop is used to traverse the string. A counter is initialized to 1 for the current character, and the next character is compared to the current one. If they match, the counter increases, and the loop advances to the next character. This process continues until a different character is found or the end of the string is reached. When the repeated sequence ends, the character and its count are printed together, and the counter is reset for the next new character. This method is repeated for every portion of the string, providing a complete and compressed version of the original input.

One of the strengths of this program is that it’s easy to understand and doesn’t require any complex data structures or libraries. It relies solely on the standard C string library <string.h> for calculating string length, and basic functions like printf and scanf for input and output. This simplicity makes it an excellent introduction to both string handling and algorithmic thinking in C. Additionally, the program helps solidify the understanding of loops, conditionals, and how to work with character arrays—a key skill for any C programmer.

The result of the program is printed directly to the screen, showing the compressed output clearly. For example, if a user enters the string “aaaabbcc”, the program would output “a4b2c2”. This shows that the string was effectively compressed by summarizing repeating characters in fewer symbols. Although RLE doesn't always reduce the size (for example, "abc" becomes "a1b1c1"), it serves as a foundational example of how compression can be approached algorithmically.

In summary, this program serves as a great demonstration of how repetition in data can be optimized through compression. It’s a simple yet powerful example of how small algorithms can solve meaningful problems. The logic used here mirrors many real-world systems that require encoding, storage, or data transmission optimization, making this a valuable learning experience for anyone studying programming or data structures.

#OUTPUT:

![Image](https://github.com/user-attachments/assets/89d27c9b-14f2-4b01-a410-b4f322942940)
