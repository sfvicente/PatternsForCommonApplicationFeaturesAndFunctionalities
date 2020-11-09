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


### Never use any references to accounts or users in a password reset URL.

When using URL tokens for password resets

In addition to be randomly generated and unique to the each instance of the reset process, the URL should not contain any external references accounts or users. For example, see
the following reset URL:

```
https://www.mydomain.com/resetpassword/?username=johndoe
```

An URL such as this discloses which user it's facilitating the reset for, which exposes a mechanism for a malicious user to abuse the system.
<br>


### Always limit the duration of the password reset token.

A password reset URL should expire not only after the process is completed but also after a pre-defined time. If the token expires after an appropriate period, it ensures
that the process has to be completed within a certain duration. Keeping the expiration window to a minimum reduces the possibility of attackers re-using password reset links, 
such as in the case of compromised email accounts.

Always limit the duration in which a URL token can be used to the minimum possible without creating issues to the users.
<br>


### Consider using a token duration of 20 minutes to a maximum of one hour.

When setting the duration of a token, one must take into account email delivery and reliability.

todo: complement description
<br>


### Ensure the URL reset tokens are stored securely.

todo: complement description
<br>


