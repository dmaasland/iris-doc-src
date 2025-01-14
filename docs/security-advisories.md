# Security Advisories

This page lists all security advisories that have been published for the code released by DFIR-IRIS.

## [CVE-2021-32737](https://github.com/dfir-iris/iris-web/security/advisories/GHSA-gc6j-6276-2m49) <small>_ May 24, 2023 _</small>

| CVE ID | Github ID | Severity | Impacted product |  
|--------|-----------|-----------|-------|
| [CVE-2021-32737](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-30615) | [GHSA-gc6j-6276-2m49](https://github.com/dfir-iris/iris-web/security/advisories/GHSA-gc6j-6276-2m49) | Moderate - CVSS3 4.6/10 | iris-web |

### Description
A stored Cross-Site Scripting (XSS) vulnerability has been identified in `iris-web`, affecting multiple locations in versions prior to `v2.2.1`. The vulnerability allows an attacker to inject malicious scripts into the application, which are then executed when a user visits the affected locations. This can lead to unauthorized access, data theft, or other related malicious activities.

An attacker need to be authenticated on the application to exploit this vulnerability.


### Affected versions
- `iris-web` < `2.2.1`
-  `iris-web` > `2.0.0` and < `2.2.1` while not using the alerting feature are not impacted.

### Fixed versions
- `iris-web` >= `2.2.1`

### Workarounds
No workaround is available.

