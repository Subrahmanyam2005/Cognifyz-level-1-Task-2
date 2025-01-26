# Cognifyz-level-1-Task-2
Description of the Code

1. Input Handling:

The program starts by prompting the user to enter a word or phrase.

The input is read using the Scanner class.



2. Input Preprocessing:

To ensure the palindrome check is accurate, spaces, punctuation, and case differences are ignored.

This is achieved using:

replaceAll("[^a-zA-Z0-9]", ""): Removes all non-alphanumeric characters.

toLowerCase(): Converts the string to lowercase for uniformity.




3. Palindrome Check:

The isPalindrome method performs the actual palindrome check.

Two pointers (left and right) are initialized at the start and end of the string, respectively.

A loop iterates through the string:

Characters at the left and right pointers are compared.

If any mismatch is found, the method returns false.

If the pointers meet without mismatches, the method returns true.




4. Output:

Based on the result of the isPalindrome method, the program prints whether the input is a palindrome or not.



5. Edge Cases:

The code handles empty strings, single characters, and phrases with spaces and punctuation.





---

Sample Input and Output

Input:

A man, a plan, a canal: Panama

Output:

The given word or phrase is a palindrome!

Input:

Hello, World!

Output:

The given word or phrase is not a palindrome.
