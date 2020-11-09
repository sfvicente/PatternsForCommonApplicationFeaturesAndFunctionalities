# Password Reset | URL Tokens

URL Tokens are a mechanism for resetting passwords in which identifiers or tokens are passed in the query string of a URL. The link is normally sent to users via email.
<br>


### Use URL tokens for a simple and fast implementation for password resets.

Using a URL token mechanism is the simplest option to reset passwords for users.

todo: complement description
<br>


### Ensure that generated tokens or codes randomly generated using a cryptographically strong algorithm.

todo: complement description
<br>


### Always ensure that generated tokens or codes are long enough to protect against brute-force attacks.

todo: complement description
<br>


### Make the password reset URLs a one-time process by invalidating the token after the process is finished.

All tokens should be invalidated once the password reset process is completed. This will ensure that URL tokens cannot be used again. If the password reset process has been 
completed successfully, there is no more need for thd links or the token. It limits both the opportunity window for using leaked passwords and the risk of other possible attacks.

<br>


### Do not use any references to the account in the password reset URL.

Each password reset URL should be unique to the current instance of the reset process. Besides being random, it should not contain any external references to the account for which it’s facilitating the reset.
For example, a reset URL should never use  “https://myapp.com/Reset/?username=JohnDoe”. It exposes a way of abusing the system.
<br>


### Always limit the duration of the password reset token.

A password reset URL should expire not only after the process is completed but also after a pre-defined time. If the token expires after an appropriate period, it ensures
that the process has to be completed within a certain duration. Keeping the expiration window to a minimum reduces the possibility of attackers re-using password reset links, 
such as in the case of compromised email accounts.

Always limit the duration in which a URL token can be used to the minimum possible without creating issues to the users.
<br>


