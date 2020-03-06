# Krypton4 - Substitution Cipher  
  
[Krypton Level 3 &rarr; 4](https://overthewire.org/wargames/krypton/krypton3.html)  
  
Now we are going to need to be a little bit more clever. This level is using a [polyalphabetic](https://en.wikipedia.org/wiki/Polyalphabetic_cipher) [substitution cipher](https://en.wikipedia.org/wiki/Substitution_cipher) which means thare are 25 factorial possible keys. Which is 1.551121e+25 possible combinations if we were to try brute force. Luckily for us, we have some large blocks of text that we know are:  
1. In English  
2. Encypted with the same key as the password  
  
This means we can do some [frequency analysis](https://en.wikipedia.org/wiki/Frequency_analysis) on the given text to predict what common substitutions are because we know the expected frequency of letters in the English language.  
  
  
