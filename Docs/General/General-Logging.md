# General | Logging
<br>


### Use a standard and easily configurable logging framework.

TODO: Add description.

<br>


### Avoid synchronous logging to prevent blocking application execution.

Write logs asynchronously with a buffer or queue, so that application execution isn't affected.

TODO: Add description.

<br>


### Encrypt logging data in transit.

Use transport level security such as HTTPS to ensure the integrity and confidentiality of transport data. 

TODO: Add description.

<br>


### Use fault-tolerant protocols for transmission to ensure reliability.

Use TCP or RELP to transmit logs and avoid losing packets.

TODO: Add description.

<br>


### Do not log sensitive data.

The following can be considered sensitive data:
- Personally identifiable data
- Health Data
- Financial Data
- Passwords

TODO: Add description.

<br>


### Do not store logs inside the same availability zone or regions of your applications.

In case of outages, natural disasters or abnormal data center issues, having the logs in a different availability zone or region, will still allow for analysis and troubleshooting.

TODO: Add description.

<br>


### Always optimise logging storage data for query performance.

TODO: Add description.

<br>


