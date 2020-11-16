# Security | REST APIs

REST APIs are application programming interfaces that use Representational state transfer (REST) as the software architectural style. REST defines a set of constraints that are
employed when creating services for the web.
<br>


## Input Validation
<br>


### Always define a maximum allowed size for requests and reject those exceeding the limit.

todo: add description.

<br>


### Always return an HTTP response status `413 Request Entity Too Large` to requests that exceed the maximum allowed size.

todo: add description.

<br>


## Error Handling
<br>


### Always avoid revealing unnecessary details of failed calls by replying with generic error messages.

todo: complement description

<br>


### Do not return internal technical information to clients.

todo: complement description

Examples of internal technical details are an operation callstack or an exception with database errors.

<br>


## Security Headers
<br>

### Always include the `Cache-Control: no-store` header in API responses.

todo: complement description

Additional Tags: HTTP Headers
<br>


### Always include the `Content-Security-Policy` header in API responses.

todo: complement description

Use the `Content-Security-Policy` header to protect the application against clickjacking attacks:

```
Content-Security-Policy: frame-ancestors 'self';
```

Additional Tags: HTTP Headers
<br>


### Always specify the `Content-Type` as `application/json` for JSON responses.

todo: add description

Additional Tags: HTTP Headers
<br>


### Always specify the `Strict-Transport-Security` header to require connections over HTTPS and to protect against spoofed certificates.

todo: add description

Additional Tags: HTTP Headers
<br>