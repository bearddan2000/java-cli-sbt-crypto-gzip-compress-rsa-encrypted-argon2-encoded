# java-cli-sbt-crypto-gzip-compress-rsa-encrypted-argon2-encoded

## Description
Encrypt and decrypt password with RSA
encoded with argon2.

When storing a password it is best practice
to use a one-way hash such as bcrypt, scrypt,
or argon2.

## Tech stack
- java
- sbt

## Docker stack
- hseeberger/scala-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- https://mkyong.com/java/java-password-hashing-with-argon2/
- https://paragonie.com/blog/2016/02/how-safely-store-password-in-2016
