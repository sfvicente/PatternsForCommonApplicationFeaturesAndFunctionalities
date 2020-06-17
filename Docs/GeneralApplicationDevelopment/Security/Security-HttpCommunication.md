# General | Security | HTTP Communication
<br>


# General | Security | HTTP Communication
<br>


### Always implement HTTPS security.

TODO: Add description

<br>


### Always redirect all HTTP traffic to HTTPS.

TODO: Add description

<br>


### Always use an updated version of TLS.

TODO: Add description

<br>


### Implementing the `X-XSS-Protection` security header to help prevent cross-site scripting attacks.

TODO: Add description

<br>


### Consider using the `Referrer-Policy` header to prevent leaking the referrer value.

TODO: Add referrer explanation

To prevent leaking the referrer value, set `Referrer-Policy` header to `no-referrer`:

```
"Referrer-Policy": "no-referrer"
```

<br>


### Remove the `X-AspNet-Version` from the response header to prevent disclosing server information and the .NET framework information.  

The `X-AspNet-Version` specifies the version of ASP.NET used.

TODO: Add description

<br>


### Remove the `X-Powered-By` from the response header to prevent disclosing server information and the .NET framework information.  

The `X-Powered-By` specifies that the website is powered by ASP.NET.

TODO: Add description

<br>


### Remove the `Server` from the response header to prevent disclosing server information and hosting technology.  

The `Server` specifies web server version (IIS version).

TODO: Add description

<br>


### Use the `Feature-Policy` header to limit access to browser features & APIs.

The HTTP `Feature-Policy` header provides a mechanism to allow and deny the use of browser features in its own frame, and in content within any `<iframe>` elements in the document.

TODO: Add description

<br>


### Use the `Content-Security-Policy` to implement a strong content security policy to detect and mitigate certain types of code injection attacks.

Content security policy is a layer of security that helps detect and mitigate certain types of attacks, including Cross Site Scripting (XSS) and data injection attacks.

Syntax:

`
Content-Security-Policy: <policy-directive>; <policy-directive>; ...
`

Example:

`
Content-Security-Policy: default-src 'none'; script-src 'self'; img-src 'self'; style-src 'self'; connect-src 'self';
`

<br>


### Use the `X-Frame-Options` header to disable iframe embedding to prevent clickjacking attacks.

The `X-Frame-Options` HTTP response header can be used to indicate whether a browser should be allowed to render a page in a <frame>, <iframe>, <embed> or <object>. It can be used to ensure that a web site's content is not embedded into other sites, therefore avoiding clickjacking attacks.

There are two directives that can be used:

`
X-Frame-Options: DENY
X-Frame-Options: SAMEORIGIN
`

<br>


