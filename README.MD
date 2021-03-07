Keeping your website safer

Email and Password

- For users, emails and passwords are stored in a database, once you login/register, the email and passwords will be stored/matched with the records in the database

Database Encryption

- Due to databases storing the direct strings, we want to have additional encryption so that, in the case of someone hacking into a database and seeing the raw email and passwords.

- A simple example of this is Caesar Cipher, in which the each letter becomes a new letter after being shifted along the alphabet x number of letters

- All types of encryption are generally some form of way that scrambles the information that requires a key to unscramble it

Utilizing environmental variables to keep secret keys safe

- Using .env files that are exclusive to local machines (and are in .gitignore) to ensure that api keys and other secrets are not available to the public

Hashing

- Hashing is a bit different from the regular encryption, as it does not require a key to scramble and unscramble passwords. Instead, its put through a hash function which the result is stored in the database. Hash utilizes math to make a password nearly un-hashable.

Salting

- Adds additional security on top of hashing, this is mainly done by adding a random set of characters after the password then throwing it through a hash function, additional characters that are hashed exponentially increase the complexity and thus the time it would take to crack it. bCrypt does this well.

Side notes:

- Utilizing passportjs allows user authentication to be so much easier
