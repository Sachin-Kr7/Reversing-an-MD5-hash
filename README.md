# Reversing-an-MD5-hash
reverse an MD5 hash using a brute force technique where we simply 'forward hash' all possible combinations of characters in strings.

This following is an example of hash value:
0bd65e799153554726820ca639514029

The simplest brute force approach generally is done by writing a series of nested loops that go through all possible combinations of characters. This is one of the reasons that password policies specify that you include uppper case, lower case, numbers, and punctuation in passwords is to make brute force cracking more difficult. Significantly increasing the length of the password to something like 20-30 characters is a very good to make brute force cracking more difficult.

This application will take an MD5 value like "81dc9bdb52d04dc20036dbd8313ed055" (the MD5 for the string "1234") and check all combinations of four-digit "PIN" numbers to see if any of those PINs produce the given hash.

User can enter an MD5 string and request that you reverse-hash the string. If you can reverse hash the string, print out the PIN:

     PIN: 1234

If the string does not reverse hash to a four digit number simply put out a message like:

     PIN: Not found

It prints out the first 15 attempts to reverse-hash including both the MD5 value and PIN that you were testing. It also prints out the elapsed time for your computation as shown in the sample application.

