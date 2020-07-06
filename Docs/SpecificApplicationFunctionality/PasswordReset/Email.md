# Password Reset | Email
<br>

### Do no send any sensitive data in the password reset emails.

Non-encrypted email is an insecure channel. No sensitive data should be send via non-encrypted email as the transport layer for it is not secure.

In additional to the lack of confidentiality of the in-transit information, content is normally persisted in storage. It can be copied, forwarded and redistributed. Also, the same information can be is accessible by administrative personnel, be a target of malicious software and hackers.
<br>


### Use a relevant and readable _Subject_ and _From_ name in the email.

It's important for the user to be able to identify and locate the password reset email as soon as arrives in the inbox.

Although the _Subject_ and _From_ are not critical to the process, facilitating the location will will reduce friction and ensure a smoother process.


### Identify who initiated the reset process in the reset email.

A password request mechanism is prone to abuse. You can help the recipient by supplying more information regarding the request.

For example, you include the IP address, time, browser and country of the originating source. This will the user identify and validate the request.

TODO: Example
<br>


### Include information in the email to let the recipient know that the reset URL will expire as well as when the link expires.

The recommend practice is to have the expiration window as small as possible. A password reset link might expire before the recipient has an opportunity to access their email and complete the process. It’s important to clearly communicate both the fact that the link expires as well as when the link will expire.

Include a sentence in the email to let the recipient know the password reset URL that it expires and how long until the link expires. For convenience, you can include a direct link to where users can initiate another password reset request if the link has expired.
<br>


