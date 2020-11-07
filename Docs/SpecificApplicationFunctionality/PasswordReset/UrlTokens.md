# Password Reset | URL Tokens

Url Tokens are a mechanism for resetting passwords in which identifiers or tokens are passed in the query string of a url. The url is normally sent to users via email.
<br>


### Make the password reset URLs a one-time process.

All URLs and associated tokens should be invalidated once the password reset process is completed. There is no more need for the the URL or token if the process has been complete successfully. It also limits both the opportunity window and the risk of possible attacks.
<br>


### Do not use any references to the account in the password reset URL.

Each password reset URL should be unique to the current instance of the reset process. Besides being random, it should not contain any external references to the account for which it’s facilitating the reset.
For example, a reset URL should never use  “https://myapp.com/Reset/?username=JohnDoe”. It exposes a way of abusing the system.
<br>


### Limit the duration of the password reset URL or token.

A password reset URL should expire after the process is completed or after a pre-defined period. It ensures that the process is completed within a certain duration. Keeping the expiration window to a minimum reduces the possibility of attackers re-using links, for example, if the user's email is later compromised.
Limit the duration of the URL to the minimum possible without causing issues to your users.  Consider email delivery and reliability. Recommended duration should be 20 minutes with a maximum of one hour.
<br>


