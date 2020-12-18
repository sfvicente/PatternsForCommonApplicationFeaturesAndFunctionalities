# Session Management | General
<br>


### Consider performing loggging of all session activities.

Similar to error logging, session logging consists of recording of major session activities. Examples of events that should be saved are the creation and discard of user
sessions.

todo: complement description
todo: add code examples

Additional Tags: Security, Logging
<br>


### Always remove or expire session cookies at logout.

When managing sessions, if an application performs a logout process, session cookies should be deleted or expired.

todo: complement description
todo: add code examples

Additional Tags: Security, Cookies
<br>


### Do not switch a given session from HTTP to HTTPS, or vice-versa.

When a session is swiched from HTTP to HTTPS, it will allow the session ID to be captured in the network.

todo: complement description
todo: add code examples

Additional Tags: Security, HTTP Communication, HTTPS
<br>


