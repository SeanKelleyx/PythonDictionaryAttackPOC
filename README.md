PythonDictionaryAttackPOC
=========================

Proof of concept for class, crack default Unix hash and salt encryption given attacker has /etc/passwd .
=========================


In response to my discussion post this is a good reason to use shadow 
and insure your users are educated about strong passwords, and certainly 
not using a dictionary word.

-------------------------

the file password.txt is representative of info in the /etc/passwd file
there is the user Imma Victim who has used a dictionary word "egg"
for her password, and there is root who has not.

-------------------------

the file dictionary.txt is a word list, a real attacker would aquire a 
much more comprehensive list allong with a collection of common passwords.

-------------------------

the code works by using the dictionary.txt file to encrypt each dictionary 
word, to find a match in the encryption.

Hope you like it.
