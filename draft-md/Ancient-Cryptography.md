# What is cryptography

Imagine two friends Alice and Bob that share a secret are seperated.
This requires them to communicate private information distantly and discretely.

Eve, however is able to eaevesdrop on every single message sent between Alice and Bob.
If the message was simply sent via the information channel that Eve is listening on, Eve would eventually know what Alice and Bob are communicating about. 
Sooner or later, Eve would know their secret too.
This cannot be good.

Alice and Bob decide to communicate using some kind of secret code that Eve is unaware of.
Thus, Eve would not be able to comprehend what Alice and Bob are talking about.

The followinng __analogy__ might be helpful.
Alice and Bob know the numerical code to a combination lock.
It is presumed that Eve doesn't not know the numerical code that unlocks the lock being used.
Alice decides to write her message and lock it in a box using the lock to whose key only Alice and Bob know.
As the box moves from Alice to Bob, Eve intercepts but is unable to access Alice's message to Bob.
Upon the untampered locked box reaching Bob, Bob unlocks the box using code that he already knew.

Thus the message has reached from Alice to Bob and despite Eve being able to Eavesdrop on the message being sent and was unable to learn the contents of the box ensuring the secret remains between Alice and Bob.

Alice and Bob have hence managed to communicate in secrecy even if Eve intercepted their message in transit.

In this analogy, locking the box to conceal the message being sent is equivalent to Encryption and unlocking the box to reveal the message is equivalent to decryption.

Encrypted messages are encrypted such that Eve, the evesdropper is unable to learn about the message even if intercepted.	
