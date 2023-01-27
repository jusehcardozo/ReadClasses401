Jose Cardozo
01/26/2023

https://www.ssh.com/academy/pki


Public Key Infrastructure (PKI)

Public Key Infrastructure (PKI) is a technology for authenticating users and devices in the digital world. The basic idea is to have one or more trusted parties digitally sign documents certifying that a particular cryptographic key belongs to a particular user or device. The key can then be used as an identity for the user in digital networks.

The users and devices that have keys are often just called entities. In general, anything can be associated with a key that it can use as its identity. Besides a user or device, it could be a program, process, manufacturer, component, or something else. The purpose of a PKI is to securely associate a key with an entity.

The trusted party signing the document associating the key with the device is called a certificate authority (CA). The certificate authority also has a cryptographic key that it uses for signing these documents. These documents are called certificates.

In the real world, there are many certificate authorities, and most computers and web browsers trust a hundred or so certificate authorities by default.

A public key infrastructure relies on digital signature technology, which uses public key cryptography. The basic idea is that the secret key of each entity is only known by that entity and is used for signing. This key is called the private key. There is another key derived from it, called the public key, which is used for verifying signatures but cannot be used to sign. This public key is made available to anyone, and is typically included in the certificate document.

Common Uses of Certificates
Secure Web Sites - HTTPS
The most familiar use of PKI is in SSL certificates. SSL (Secure Sockets Layer) is the security protocol used on the web when you fetch a page whose address begins with https:. TLS (Transport Layer Security) is a newer version of the protocol. In practice, most websites now use the new version.

With HTTPS, certificates serve to identify the web site you are connecting to, to ensure that no-one can eavesdrop on your connection or, for example, inject fraudulent wire transfers or steal credit card numbers.

Security Limitations of Public Key Infrastructure
The main weakness of public PKI is that any certificate authority can sign a certificate for any person or computer. Certificate authorities exist in many countries, some of which have rather authoritarian or even potentially hostile governments. Sometimes certificate authorities create or are coerced to create certificates for parties they have no business vouching for.

Among other things, intelligence agencies can use fraudulent certificates for espionage, malware injection, and forging messages or evidency to disrupt or discredit adversaries. For this reason, only limited trust should be placed on certificates from public certificate authorities.
