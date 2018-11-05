# Protect your data with GnuPG on Linux on IBM Z and LinuxONE

## What is GnuPG aka. GNU Privacy Guard
GnuPG (GPG) is an open source version of PGP that allows you to sign and and also encrypt a file or an email message. 
This is useful to maintain integrity of the message or file and also protects the confidentiality of the information contained within the file or email. 
Not only can it provide Data at Rest protection but also Data in Motion protection once the message has been sent across the network.
GPG is used to identify yourself and authenticate your communications, including those with people you do not know. 
GPG allows anyone reading a GPG-signed email to verify its authenticity. In other words, GPG allows someone to be reasonably certain that communications signed by you actually are from you. GPG is useful because it helps prevent third parties from altering code or intercepting conversations and altering the message.

## Installing GnuPG
Check that it is already installed? ($ ‘which gpg’). It is a common package to many distributions. In case it is not installed by default, please issue the following command:
```
yum install gpg
```

## Building a simple use case

GnuPG is a tool for secure communication. This git is about a quick-start guide that covers the core functionality of GnuPG. 
This includes keypair creation, exchanging and verifying keys, encrypting and decrypting documents, and authenticating documents with digital signatures. 
It also does not explain how to use GnuPG wisely.

Let's play Alice and Bob in this GPG relationship.

## Let's go! Let's generate some pair of keys!

GnuPG uses public-key cryptography so that users may communicate securely. 
In a public-key system, each user has a pair of keys consisting of a private key and a public key. 
A user's private key is kept secret; it need never be revealed. 
The public key may be given to anyone with whom the user wants to communicate. 
GnuPG uses a somewhat more sophisticated scheme in which a user has a primary keypair and then zero or more additional subordinate keypairs. 
The primary and subordinate keypairs are bundled to facilitate key management and the bundle can often be considered simply as one keypair.

The command-line option --gen-key is used to create a new primary keypair.

Create a new set of public/private keys:
```
ALICE% gpg --gen-key
gpg (GnuPG) 0.9.4; Copyright (C) 1999 Free Software Foundation, Inc.
This program comes with ABSOLUTELY NO WARRANTY.
This is free software, and you are welcome to redistribute it
under certain conditions. See the file COPYING for details.

Please select what kind of key you want:
   (1) DSA and ElGamal (default)
   (2) DSA (sign only)
   (4) ElGamal (sign and encrypt)
Your selection?
```

The command will generate key files under:
```

```


## 

## 

## 

## 
