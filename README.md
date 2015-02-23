Public keys
-----------

Add these to a server by:

1) Add a user called odi

2) Set the password of the user odi to something no one is ever going to remember

3) Add the keys to the authorized_keys file for this user

4) Add the following to the sudoers file so that odi can su without a password 

odi     ALL=(root)NOPASSWD: ALL
