# Goldmansaches-Crack-leaked-password-database

What type of hashing algorithm was used to protect passwords?
What level of protection does the mechanism offer for passwords?
What controls could be implemented to make cracking much harder for the hacker in the event of a password database leaking again?
What can you tell about the organization’s password policy (e.g. password length, key space, etc.)?
What would you change in the password policy to make breaking the passwords harder? 

After conducting analysis it was determined that organization uses a password hashing algorithm (MD5) which will provide very little protection in the event of a password database leaking.MD5 hash code strings also are limited to 128 bits.

As a result of this analysis the three major techniques are proposed to increase the overall level of password protection:

The first is bcrypt not only does bcrypt include salts, it also makes brute force attacks substantially more difficult

second option is scrypt. Like bcrypt, scrypt is a CPU-hardened function, but it also has the advantage of being memory-hard.
That means it deliberately consumes more memory resources scrypt hash, you can also control how much memory is required. 
This means you can make computing scrypt hashes expensive by forcing attackers to acquire a large amount of both compute and memory resources.

Another less-established but promising hashing mechanism, Argon2, seems to offer the most flexibility yet.

As you look for the right hashing approach, the main thing to remember is that you shouldn’t try and roll your own hashing functions.
It’s an incredibly complex space with some rarified math. Instead, use established libraries and accepted algorithms. 
A little due diligence and extra care now will save your organization considerable embarrassment in the future, not to mention potential regulatory fines.

you can include many things in password policy:

01.Use Password Encryption
02.Use Multi-Factor Authentication
03.Avoid Using Dictionary Passwords
04.password should contain special characters,small letters,capital letters,numbers
