Expect_check_password
=====================

This script should help in verifying the root password for list of servers. 
So, this script can be called in for loop. 
This also take in account not to try incorrect password more than twice so as to avoid the possibility or account getting locked. 

The syntax is :
./check_root_password <server_name> <User name> <Root Password> <Identification key for login> 

Here the user name can be a normal user or the root user. In case of normal user, it expects that the authentication is key based. 
Identification key is also optional and is only necessary when the identicfication is not at its default path. 
