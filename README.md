# Im-Lab Encrypting/Decrypting Data Procedures

## Tool and password files 
* Tool file: Imlab_encryption_tool.sh
* Password file: **pass**

## Change password file permission as a root with chmod 
* ```chmod 400 **pass**```
* save it in a safe place (e.g. ~/.ssh/)

## Encrypt/Decrypt a single file
* Encryption usage: ```sh imlab_encryption_openssl.sh ~/.ssh/pass test1/README.md encrypt```
* Decryption usage: ```sh imlab_encryption_openssl.sh ~/.ssh/pass test1/README.md decrypt```

## Encrypt/Decrypt a folder 
* Encryption usage: ```sh imlab_encryption_openssl.sh ~/.ssh/pass test1 encrypt```
* Decryption usage: ```sh imlab_encryption_openssl.sh ~/.ssh/pass test1 decrypt```
