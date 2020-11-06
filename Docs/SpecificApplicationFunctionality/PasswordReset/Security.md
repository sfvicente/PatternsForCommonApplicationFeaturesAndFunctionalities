# Password Reset | Security
<br>

### Record the _IP Address_ and _User Agent_ of who requested the reset

TODO: Add description

<br>


### Never send referrer information in requests made within a reset password page.

Ensure that the reset password page does not send referrer information in requests. This can be achieve by adding the `Referrer Policy` tag with the `noreferrer` value which
will prevent referrer leakage.

The `Referrer-Policy` HTTP header determines what referrer information is included in requests. This data is sent via the `Referer header`.

TODO: complement description

<br>


### Never rely on `Host` header for constructing reset URLs in an application.

TODO: Complement description

By using a `Host` header value to build password reset urls, the application becomes susceptible to Host Header Injection attacks.

TODO: Add example

As a solution, either hard-code the hosts in an application either in code or in a configuration file or validate the domain against a list of allowed trusted domains.

<br>


### Consider implementing measures to prevent users brute-forcing tokens in the URL.

Malicious individuals can attempt to exploit password recovery urls by means of brute-force. Automated systems can construct urls with generated tokens with the objective of
finding valid tokens or impact system performance.

To prevent damage from abuse of the token urls, consider using a mechanism such as rate limiting.

TODO: complement description

<br>