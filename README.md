# FTPSClient

## What is it?
This is a fork of Alex Pilotti's [FTPSClient](https://ftps.codeplex.com/).  
The modifications made to this library are to make it less "exceptional," and more standard.
For example, when renaming a file, a simple bool return should suffice and won't throw an exception
if the file can't be renamed.