# Class 33

## Authentication & Production Server

[Home](https://daviey52.github.io/reading-notes/)

JSON Web Token (JWT) is an open standard that defines a compact and self-contained way for
securely transmitting information between parties as a JSON object. This information can be
verified and trusted because it is digitally signed. JWTs can be signed using a secret (with
the HMAC algorithm) or a public/private key pair using RSA or ECDSA.
Signed tokens can verify the integrity of the claims contained within it, while encrypted
tokens hide those claims from other parties. When tokens are signed using public/private key
pairs, the signature also certifies that only the party holding the private key is the one that
signed it.

## Some of the scenarios that JWT might be useful

Authorization: This is the most common scenario for using JWT. Once the user is logged
in, each subsequent request will include the JWT, allowing the user to access routes,
services, and resources that are permitted with that token. Single Sign On is a feature
that widely uses JWT nowadays, because of its small overhead and its ability to be easily
used across different domains.

Information Exchange: JSON Web Tokens are a good way of securely transmitting
information between parties. Because JWTs can be signed—for example, using
public/private key pairs—you can be sure the senders are who they say they are.
Additionally, as the signature is calculated using the header and the payload, you can
also verify that the content has been tampered with.

In authentication, when the user successfully logs in using their credentials, a JSON Web Token
will be returned. Since tokens are credentials, great care must be taken to prevent security
issues. In general, you should not keep tokens longer than required.

The JWT is acquired by exchanging an username + password for an access token and an refresh
token. The access token is usually short-lived (expires in 5 min or so, can be customized
though).

The refresh token lives a little bit longer (expires in 24 hours, also customizable). It is
comparable to an authentication session. After it expires, you need a full login with username +
password again.

At first glance the refresh token may look pointless, but in fact it is necessary to make sure the
user still have the correct permissions. If your access token have a long expire time, it may take
longer to update the information associated with the token. That’s because the authentication
check is done by cryptographic means, instead of querying the database and verifying the data.
So some information is sort of cached.

There is also a security aspect, in a sense that the refresh token only travel in the POST data.
And the access token is sent via HTTP header, which may be logged along the way. So this also
give a short window, should your access token be compromised.
