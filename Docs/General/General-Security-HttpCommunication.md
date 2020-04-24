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