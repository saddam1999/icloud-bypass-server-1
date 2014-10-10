icloud-bypass-server
====================

For XAMPP need to uncomment lines 99-100 and comment lines 102-103 in files "deviceActivation".

Check path of XAMPP (c:\xampp\) and openssl (c:\xampp\apache\bin\).

This sources has problem with signed certificate and accounttoken. iDevice do not accept them. 

In all *.cmd files need to modify path to openssl.exe and openssl.cnf for correct execution.

Changes from version 35 (isrv_35.zip):
- added XAMMP support
- added decrypt_private_keys.cmd for decryption private key
- some minor modifications.

For entertainment purposes only.
