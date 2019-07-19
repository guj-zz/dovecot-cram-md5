# dovecot-cram-md5
## HMAC-MD5/CRAM-MD5 Hash Generator for Dovecot

HMAC-MD5 is a challenge-response authentication protocol. In order to avoid the storage of the password in clear text, Dovecot allows one to generate the "context" value. This is an intermediate hash generated from the password during the authentication. This Python module generates HMAC-MD5 contexts, which can be used by Dovecot for the CRAM-MD5 authentication method.

### References:
https://tools.ietf.org/html/draft-ietf-sasl-crammd5-10

https://tools.ietf.org/html/rfc2104

### Origin

The owner of this repository does not claim to be the author of this Python module. The source code apparently has no home right now. It is available under the GPLv2 license, "Copyright (C) 2009  Asad Saeed (http://www.acidseed.com/)". It has also been published on PyPI by an unrelated packager, see https://pypi.org/project/dovecot-cram-md5/. The purpose of this repository is to keep the source code available.

