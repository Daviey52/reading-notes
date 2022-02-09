# Class Eightteen

[Home](https://daviey52.github.io/reading-notes/)

## Cryptography

One of the earliest encryption techniques is the Caesar Cipher, that was invented by Julius Caesar more than 200 years ago to communicate with his allies.

The Caesar Cipher is a simple substitution cipher that replaces each original letter with a different letter in the alphabet by shifting the alphabet by a certain number.
According to historical records, Caesar always used a shift of 3. As long as his message recipient knew the shift amount. It was trivial for them to decode the message.
Three main techniques that can be used to crack the cipher include frequency analysis, know plaintext and brute force.

Human language tend to use certain letters more than other. For instance, ‘E’ is the most popular letter in English language. We can analyze the frequency of the characters in the message and identify the most likely in this instance letter ‘E’ and narrow down the possible shift amount based on that.
If an enemy already knew some part of the plaintext, it would be easier for them to crack the rest of the encrypted version.
Since there are only 25 possible shift, an enemy could take time to tyr out each and find the one that yielded a sensible message.

Whenever we are considering a possible encryption technique we need to consider all these aspect. How easy it is to encrypt, how easy it is to decrypt and importantly how easy it is for nefarious individual to crack the code.
