# Password Reset | General

The *Password Reset* mechanism, also known as *Forgot Password* is a service that allow a user to request a change of their current password. It is a required component to implement
user management systems.
<br>


### Never disclose if a user exists with the password recovery mechanism.

When triggering a request to reset a password, always return a consistent message for both existent and non-existent user accounts. This prevents
attackers to determine if an account exists in the system.

TODO: add example


The output of the operation, should never disclose that the account hasn't been found or that the user does not exist.

TODO: Complement description.

<br><br>


### Always ensure that the time the system takes to respond to a password reset request is consistent.

If the response time is consistent, then it won't give an attacker, clues about the existence of accounts.

TODO: Complement description.
<br>


### Do not generate a new password and send it via email

Generating a password and sending it via email creates a password that will be persisted on the servers of the mail provider. It is also sent over an insecure channel<small>**[1]**</small>.

If a password is stored in an email, this will make it available to whoever obtains access to your inbox. When synchronization or backups are enable, replication of email data will copy the password information to other devices increasing the risk of exposure.

If a password is generated and sent via email, a malicious user can lock the account owner continuously resetting the password.

<small>**[1]** see 'Do no send any sensitive data in the password reset emails.' in Password Reset | Email.</small>
<br>


### Provide information on how to contact support

TODO: Add description
<br>


### Consider invalidating a user's existing sessions after a password reset has been performed sucessfully.

The application can ask users if they would like to invalidate all of their existing sessions. Alternatively, the system may invalidate the sessions automatically.

TODO: Add description

Additional tags: Security, Session Management
<br>

