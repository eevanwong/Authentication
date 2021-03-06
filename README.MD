7 levels of authentication/security

1. Email and Password

For users, emails and passwords are stored in a database, once you login/register, the email and passwords will be stored/matched with the records in the database

2. Database Encryption

Due to databases storing the direct strings, we want to have additional encryption so that, in the case of someone hacking into a database and seeing the raw email and passwords.

A simple example of this is Caesar Cipher, in which the each letter becomes a new letter after being shifted along the alphabet x number of letters

All types of encryption are generally some form of way that scrambles the information that requires a key to unscramble it

3. Utilizing environmental variables to keep secret keys safe

Using .env files that are exclusive to local machines (and are in .gitignore) to ensure that api keys and other secrets are not available to the public
