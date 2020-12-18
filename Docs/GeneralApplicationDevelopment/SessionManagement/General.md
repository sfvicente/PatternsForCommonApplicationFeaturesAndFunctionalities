# Session Management | General
<br>

## Session ID
<br>


### Do not use use names for session IDs that describe or detail the purpose and meaning of the identifier.

todo: add description
todo: add code examples

Additional Tags: Security
<br>


### Always change the default session ID name provided by any web development framework used in the application development.

The name should be changed to a generic name, such as id.

todo: complement description
todo: add code examples

Additional Tags: Security
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


