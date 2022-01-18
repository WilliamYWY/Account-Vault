# Account Vault  
  
## Intro  
Using python to create a local vault to store all of your precious accounts with only one single user password.  
  
__The main tools we used:__
* Tkinter  
* sqlite  
* MySQL  

## Version
There are three versions  
* [Termainl + MySQL (No UI interface)](https://github.com/WilliamYWY/Account-Vault/blob/master/AccountSYS_terminal_version.ipynb "link")   
* [UI + sqlite file](https://github.com/WilliamYWY/Account-Vault/blob/master/AccountSYS_UIFILE_version.ipynb "link") 
* [UI + MySQL](https://github.com/WilliamYWY/Account-Vault/blob/master/AccountSYS_UISQL_version.ipynb "link")  
  
## Password Security 
To lower the risk that password might be stolen if the .db file or SQL being hacked, I use the package cryptography.fernet to generate a _Gloden KEY_ to encrypt all password beafore storing into file.  
  
The _KEY_ will be generate _only_ once when you register your ultimate password.  
__(Make sure to keep the key to decrypt the password you saved)__
