# Observability

Be ready to answer any question about the functionality or performance of your software.

### Metrics

- **RED**:
Track **Rate**, **Errors**, and **Duration** for all service requests.
- **Queue Length**:
Track the length and latency of all queues.
- **Resource Utilization**:
Track CPU, memory, disk, and network usage for all containers.


### Tracing

Tracing tells the story of a request and finds bottlenecks and opportunities for optimization.

Traces should be sample-able and should not be considered as an accurate representation of all requests.


### Logging

Logging should be **standardized in JSON format** to enable consistent parsing, filtering, and correlation across systems.  

Log levels should be used appropriately:
- **DEBUG**: Detailed information, typically of interest only when diagnosing problems.  
- **INFO**: Confirmation that things are working as expected. (always when something is created, updated, or deleted)
- **WARN**: Something unexpected happened, but the software will try to continue operating as expected.  
- **ERROR**: An issue has occurred, should point to an actionable bug or issue. Or an incident that needs to be reported and resolved.

> DEBUG logs are great for local development and troubleshooting, but obviously shouldn't be enabled in production. 
>
>However... make it possible to enable DEBUG logs *per-request* or for a short period of time, without requiring a deployment, to have better troubleshooting in production

### Alerting

Alerts must be:
- **Meaningful**: represent real issues  
- **Actionable**: clearly indicate what needs to be done  
- **Appropriate in priority**: avoid overwhelming teams
