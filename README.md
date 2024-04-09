# Easily_encrypt_a_text_The_Caesar_encryption
This Java program is a simple implementation of the Caesar cipher, a classic method of encryption. It shifts each letter in the user's input sentence by a fixed number of positions in the alphabet. The program uses an array to represent the alphabet and a predefined shift value of 3. The user is prompted to enter a sentence, which is then converted to lowercase for uniformity.

The program iterates through each character in the user’s sentence. If the character is a space, it is added as is to the new encrypted string. If the character is a letter, the program finds its position in the alphabet array and shifts it by the specified amount (3 in this case). This shift wraps around the alphabet, meaning that after 'z', it goes back to 'a'. The new character is then added to the encrypted string. Once all characters are processed, the program outputs the encrypted version of the original sentence.

This program is a basic yet practical demonstration of how Caesar cipher works.
