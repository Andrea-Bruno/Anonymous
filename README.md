# Anonymous Messenger
## Encrypted messaging application that uses the new trustless concepts of Bitcoin technology

With the advent of Bitcoin, an exciting, innovative and revolutionary technology came to life, defined as "trustless", and we took it as a starting point to create an innovative messaging app: Applications such as Telegram, Signal, Whatsapp require you to register to create the account, this creates a subject that manages the accounts of the subscribers (the back-end); the back-end is also the part that most easily suffers hacker attacks and privacy violations. We wanted to create an application without a user database in the backend, an application without a server that records any type of data about subscribers and their activity: If the backend doesn't exist then it can't be hacked! Using a concept taken from bitcoin wallets, the account is simply a pair of cryptographic keys, the private key of which is kept only by the user (in the front-end), and the public key is provided to the contact with whom you want to communicate, using the QR-code, thus avoiding the need for a "trust" subject who is aware of the accounts and consequently guesses their identity.
The project was born from the experience in developing Bitcoin wallets, and we extended it to private messaging offering a military level of security.

## Here are contained all the dependency projects to create the encrypted messaging app, which are:

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

### Secure Storage
It is a library that allows applications to save data and objects in an encrypted manner, this serves to prevent malicious software from violating the application, its settings and its data, and the information it saves permanently.
* [API Documentation](https://www.fuget.org/packages/SecureStorage/)


### NBitcoin
We used this library as a Nuget package, to implement all the underlying technology and concepts derived from the bitcoin architecture
* [External link of the project](https://www.fuget.org/packages/SecureStorage/)
