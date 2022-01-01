# Password Management | General

Password management is a set of principles and practices that provide guidance to users and system administrators on password generation, storage and administration. It aims
to help ensure the implementation of proper password security and prevent unauthorized access.
<br>

### Never store plaintext passwords. Instead, store cryptographically strong hashes of passwords.

Under any circumstances should passwords be stored in a system as plaintext.

By storing cryptographically strong hashes of passwords, it garantees that those passwords cannot be reversed.

TODO: Add description

Additional Tags: Security
<br>

### Never use deprecated hashing algorithms such as MD5 and SHA1.

TODO: Add description

Additional Tags: Security, Hashing
<br>


### Never store passwords using reversible encryption mechanisms.

Under any circumstances should reversible encryption mechanism be used to store passwords in a system. Instead, cryptographically strong hashes of the passwords should be
generated and stored.

TODO: Add description

Additional Tags: Security
<br>


### Never store passwords using custom-developed hashing mechanisms.

Under any circumstances should hashes of passwords obtained from custom-developed mechanisms be stored in a system. Instead, use cryptographically strong and proven hashing
mechanisms to generate hashes that cannot be attacked and reversed.

TODO: Add description

Additional Tags: Security, Hashing
<br>


