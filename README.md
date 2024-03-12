![ezgif-6-37b03c6ec1](https://github.com/hy011121/CryptSite/assets/75035965/5538c4dc-b2fc-4e69-abe6-9eeb1d31ea67)
  <a href="https://vimeo.com/922262322">
    <img src="https://img.shields.io/badge/%20VIDEO%20Demo%20AVAILABLE%20HERE-blue?style=for-the-badge" alt="Video Demo Available Here" />
  </a>

## Overview

CrypSite is PHP ransomware script designed to encrypt files and directories on a web server, effectively obscuring their contents. It employs a layered approach to encryption, file management, and file access control.

## Features

<p align="center">
  <img src="https://c.tenor.com/7z4SST-bVnEAAAAC/tenor.gif" alt="logo" style="max-width: auto%; height: auto;" />
</p>

`1. File and Directory Encryption:`
- This script recursively encrypts all files inside the specified directory and subdirectories.
-The encryption method used is symmetric encryption using the ??? algorithm in ??(???) mode.
-Each encrypted file will be given a ".CryptSite" extension.

`2. Creating a Decryption File:`
- This script creates a special decryption file that is required to decrypt the files that have been encrypted by CrypSite.
- This decryption file contains the necessary information, such as the encryption key used, encryption parameters, and more.

`3. Changing File and Directory Names:`
- Before encrypting a file or directory, CrypSite changes the name of the file or directory by using ??? encryption.
- This aims to obscure the identity of the encrypted file or directory.

`4. Key Encryption with ???:`
- The encryption key used is generated through the ??? function using the ??? algorithm.
- ??? is used to generate a key that is stronger than the given passphrase.

`5. Deletion of Original File:`
- After the encryption process is complete, the script will delete the original files present on the server except index.php and fm.php.

`6. .htaccess File:`
- This script creates or modifies the .htaccess file in the root directory of the web server.
- This file is used to set access rules to the web server, where in this script it is used to set all access to various status codes (e.g. 400, 401, 403, 404, and 500) to be redirected to the index.php file.

`7. Encryption Key Generation Form:`
- There is a form on the webpage that is used to enter the encryption key.
- The user is required to enter the encryption key before encrypting the file.

`8. Validation Error Message:`
- This script validates the decryption key entered by the user.
- If the encryption key does not match, an error message will be displayed on the web page.

`9. File Access Handling:`
- This script sets up the access rules to the index.php and fm.php files after completing the encryption.
- The index.php file is used to display a notification to the user that the site has been encrypted.
- The fm.php file is a file manager access control that may be used by CrypSite User to manage or monitor files that have been encrypted.

  <a href="https://t.me/Ox6218">
    <img src="https://img.shields.io/badge/BUY-NOW-blue?style=for-the-badge&logo=telegram" alt="Telegram Badge"/>
  </a>
  
## Additional Information
*do you hve question etc? contact me at: ```collee01@proton.me```
