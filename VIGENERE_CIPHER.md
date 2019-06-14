#### The Vigenere cipher is a method of encrypting alphabetic text by using a series of interwoven Caesar ciphers based on the letters of a keyword. I’m not sure what this means, but it was left lying around: blorpy gwox{RgqssihYspOntqpxs}

In order to solve the challenge, you must know the working of **Vigenere cipher**.  
The text which is said to be lying around, is actually the key. The text to be decoded is `gwox{RgqssihYspOntqpxs}`. Use an [online Vigenere cipher decoder](https://cryptii.com/pipes/vigenere-cipher), where you need to enter the key and the text to be decrypted (decoded). The flag is the result that you get after decryption.  

Another way to put it, the flag is the plain text, which is encrypted using the given key. The result of the encryption process is given. To find the value of the flag, we decrypt the given encrypted text with the key.

