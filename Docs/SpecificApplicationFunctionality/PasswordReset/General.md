# Password Reset | General

The *Password Reset* mechanism, also known as *Forgot Password* is a serice that allow a user to request a change of their current password. It is a required component to implement
user management systems.
<br>


### Do not disclose the user existence on the recovery page

TODO: Add description
<br>


### Do not generate a new password and send it via email

Generating a password and sending it via email creates a password that will be persisted on the servers of the mail provider. It is also sent over an insecure channel<small>**[1]**</small>.

If a password is stored in an email, this will make it available to whoever obtains access to your inbox. When synchronization or backups are enable, replication of email data will copy the password information to other devices increasing the risk of exposure.

If a password is generated and sent via email, a malicious user can lock the account owner continuously resetting the password.

<small>**[1]** see 'Do no send any sensitive data in the password reset emails.' in Password Reset | Email.</small>
<br>


### Make the password reset URLs a one-time process.

All URLs and associated tokens should be invalidated once the password reset process is completed. There is no more need for the the URL or token if the process has been complete successfully. It also limits both the opportunity window and the risk of possible attacks.
<br>


### Provide information on how to contact support

TODO: Add description
<br>


### Do not use any references to the account in the password reset URL.

Each password reset URL should be unique to the current instance of the reset process. Besides being random, it should not contain any external references to the account for which it’s facilitating the reset.
For example, a reset URL should never use  “https://myapp.com/Reset/?username=JohnDoe”. It exposes a way of abusing the system.
<br>


### Limit the duration of the password reset URL or token.

A password reset URL should expire after the process is completed or after a pre-defined period. It ensures that the process is completed within a certain duration. Keeping the expiration window to a minimum reduces the possibility of attackers re-using links, for example, if the user's email is later compromised.
Limit the duration of the URL to the minimum possible without causing issues to your users.  Consider email delivery and reliability. Recommended duration should be 20 minutes with a maximum of one hour.
<br>