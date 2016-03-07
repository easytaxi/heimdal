README
==

WHAT YOU CAN DO?
==
- Create your own CA
- Create Intermediate CA's
- Generate private keys on-the-fly for client certificates
- Generate CSR for Client Certificates
- Issue Client Certificates
- Export PKCS#11

PURPOSE
==
I'm missing ways of make possible HTTP's API to benefit from client side certificates. This is the main purpose of this software. It is meant to be a full featured PKI but I think that Let's encrypt[1] had been done a great job when we are talking about server side certificates, so as it is not on their intention to provide public recognized certificates for clients and normally you don't need a third party to be responsible for identifying your clients. We will focus on provide ways so you can build an REST API to issue certificates to your customers.

[1]: https://letsencrypt.org/