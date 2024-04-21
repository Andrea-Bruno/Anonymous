# Anonymous Messenger
## Encrypted messaging application that uses the new trustless concepts of Bitcoin technology

Here are contained all the dependency projects to create the encrypted messaging app, which are:

### Anonymous Messenger (path: Messenger/AnonymousMessenger/)
Minimalist application that uses the Encrypted Messaging library as its encrypted messaging engine.
Inside this repository there is also Cryptogram, it is another messaging software that shares the encrypted messaging libraries and some components with this one. Cryptogram is a derivative of this 'white label' which is more complex than this version which aims to be minimalist.

### Cryptogram (path: Messenger/AnonymousMessenger/Cryptogram)
Professional encrypted messaging application, which uses the Encrypted Messaging library as its encrypted messaging engine

### Messenger Cloud
This here is [Anonymous Messenger](https://github.com/Andrea-Bruno/AnonymousMessenger) helper software, it adopts trustless security. It offers an encrypted cloud storage where devices encrypt their contact list and other data and send it for safekeeping. This allows the recovery of the contacts, when the messenger account with the passprase is recovered. The device encrypts the data before sending it and therefore the cloud has no way of being able to see it unencrypted (trustless).

### EncryptedMessaging
Encrypted communication library to create applications similar to Telegram or Signal but with greater attention to IT security and privacy
* [API Documentation](https://www.fuget.org/packages/EncryptedMessaging)

### Communication Channel
Library that creates the socket communication channel that allows messages to be routed. Supports spooler, broken connection recovery, communication error handling and everything you need to send and receive data packets professionally
* [API Documentation](https://www.fuget.org/packages/CommunicationChannel/)

