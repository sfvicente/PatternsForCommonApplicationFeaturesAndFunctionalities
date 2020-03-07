# Password Reset | Email
<br>

### Do no send any sensitive data in the password reset emails.

Non-encrypted email is an insecure channel. No sensitive data should be send via non-encrypted email as the transport layer for it is not secure.

In additional to the lack of confidentiality of the in-transit information, content is normally persisted in storage. It can be copied, forwarded and redistributed. Also, the same information can be is accessible by administrative personnel, be a target of malicious software and hackers.
<br>


### Identify who initiated the reset process in the reset email.

A password request mechanism is prone to abuse. You can help the recipient by supplying more information regarding the request.

For example, you include the IP address, time, browser and country of the originating source. This will the user identify and validate the request.

TODO: Example
<br>



