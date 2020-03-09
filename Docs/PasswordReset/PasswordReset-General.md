# Password Reset | General
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
<br><br>
