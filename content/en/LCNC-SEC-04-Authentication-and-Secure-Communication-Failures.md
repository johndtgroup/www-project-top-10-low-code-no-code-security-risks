# LCNC-SEC-04: Authentication and Secure Communication Failures

## Risk Rating [*](https://owasp.org/www-project-top-ten/2017/Note_About_Risks)

| Prevalence | Detectability | Exploitability | Technical Impact |
| --- | --- | --- | --- |
| TBD | TBD | TBD | TBD |

## The Gist

No-code/low-code applications typically connect to business-critical data via connections set up by business users, which can often result in insecure communication.

## Description

No-code/low-code applications typically connect to business-critical data across on-prem, Saas, PaaS and cloud.
Applications use built-in connectors, which allow easy connections to various services.
Connections offer a variety of security configuration, including communication protocols, authentication flows and types of credentials used.
In many cases, connections are set up by business users, which can often result in deviation from best practice.

## Impact

TBD

## Example Attack Scenarios

Ideas to explore (TBD):
- Use of plaintext protocols (i.e. HTTP, FTP)
- Diverging from best practice (e.g. no validation of certificate, hard-coded secret)

### Scenario #1

TBD

### Scenario #2

TBD

## How to Prevent

- In production environments, limit creation of connections to dedicated personnel.
- Monitor platforms for connections that do not comply with best practice.
- Educate business users on the risks insecure communication and the need to involve security teams when setting them up.

## References

TBD