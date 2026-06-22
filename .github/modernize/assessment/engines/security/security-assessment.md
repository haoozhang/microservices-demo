# Security Assessment Report

**Generated:** 2026-06-22T06:51:39.0000000Z

## Summary

| Metric | Count |
|--------|-------|
| Total Findings | 90 |
| CVE Vulnerabilities | 81 |
| CWE Vulnerabilities | 9 |
| Total Rules Assessed | 59 |
| Rules Passed | 50 |

### By Severity

| Severity | Count |
|----------|-------|
| mandatory | 81 |
| optional | 2 |
| potential | 7 |

## CVE Findings (Dependency Vulnerabilities)

### CVE-2026-41901: Sandboxed Thymeleaf expressions vulnerable to improper recognition of unauthorized syntax patterns
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml, pom.xml:35

[CVE-2026-41901](https://github.com/advisories/GHSA-c9ph-gxww-7744): Sandboxed Thymeleaf expressions vulnerable to improper recognition of unauthorized syntax patterns

Severity: CRITICAL

Affected dependencies:
  - org.thymeleaf:thymeleaf (versions: <= 3.1.4.RELEASE, declared at pom.xml:35)
  - org.thymeleaf:thymeleaf-spring5 (versions: <= 3.1.4.RELEASE, declared at pom.xml)
  - org.thymeleaf:thymeleaf-spring6 (versions: <= 3.1.4.RELEASE, declared at pom.xml)

Recommended fix:
  - Upgrade org.thymeleaf:thymeleaf to 3.1.5.RELEASE or later
  - Upgrade org.thymeleaf:thymeleaf-spring5 to 3.1.5.RELEASE or later
  - Upgrade org.thymeleaf:thymeleaf-spring6 to 3.1.5.RELEASE or later

### CVE-2026-40478: Improper neutralization of specific syntax patterns for unauthorized expressions in Thymeleaf
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml, pom.xml:35

[CVE-2026-40478](https://github.com/advisories/GHSA-xjw8-8c5c-9r79): Improper neutralization of specific syntax patterns for unauthorized expressions in Thymeleaf

Severity: CRITICAL

Affected dependencies:
  - org.thymeleaf:thymeleaf (versions: <= 3.1.3.RELEASE, declared at pom.xml:35)
  - org.thymeleaf:thymeleaf-spring5 (versions: <= 3.1.3.RELEASE, declared at pom.xml)
  - org.thymeleaf:thymeleaf-spring6 (versions: <= 3.1.3.RELEASE, declared at pom.xml)

Recommended fix:
  - Upgrade org.thymeleaf:thymeleaf to 3.1.4.RELEASE or later
  - Upgrade org.thymeleaf:thymeleaf-spring5 to 3.1.4.RELEASE or later
  - Upgrade org.thymeleaf:thymeleaf-spring6 to 3.1.4.RELEASE or later

### CVE-2026-40477: Improper restriction of the scope of accessible objects in Thymeleaf expressions
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml, pom.xml:35

[CVE-2026-40477](https://github.com/advisories/GHSA-r4v4-5mwr-2fwr): Improper restriction of the scope of accessible objects in Thymeleaf expressions

Severity: CRITICAL

Affected dependencies:
  - org.thymeleaf:thymeleaf (versions: <= 3.1.3.RELEASE, declared at pom.xml:35)
  - org.thymeleaf:thymeleaf-spring5 (versions: <= 3.1.3.RELEASE, declared at pom.xml)
  - org.thymeleaf:thymeleaf-spring6 (versions: <= 3.1.3.RELEASE, declared at pom.xml)

Recommended fix:
  - Upgrade org.thymeleaf:thymeleaf to 3.1.4.RELEASE or later
  - Upgrade org.thymeleaf:thymeleaf-spring5 to 3.1.4.RELEASE or later
  - Upgrade org.thymeleaf:thymeleaf-spring6 to 3.1.4.RELEASE or later

### CVE-2023-20883: Spring Boot Welcome Page Denial of Service
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2023-20883](https://github.com/advisories/GHSA-xf96-w227-r7c4): Spring Boot Welcome Page Denial of Service

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot-autoconfigure (versions: >= 3.0.0, < 3.0.7, declared at pom.xml)
  - org.springframework.boot:spring-boot-autoconfigure (versions: >= 2.7.0, < 2.7.12, declared at pom.xml)
  - org.springframework.boot:spring-boot-autoconfigure (versions: >= 2.6.0, < 2.6.15, declared at pom.xml)
  - org.springframework.boot:spring-boot-autoconfigure (versions: < 2.5.15, declared at pom.xml)

Recommended fix:
  - Upgrade org.springframework.boot:spring-boot-autoconfigure to 3.0.7 or later
  - Upgrade org.springframework.boot:spring-boot-autoconfigure to 2.7.12 or later
  - Upgrade org.springframework.boot:spring-boot-autoconfigure to 2.6.15 or later
  - Upgrade org.springframework.boot:spring-boot-autoconfigure to 2.5.15 or later

### CVE-2022-22968: Improper handling of case sensitivity in Spring Framework
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-22968](https://github.com/advisories/GHSA-g5mm-vmx4-3rg7): Improper handling of case sensitivity in Spring Framework

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-context (versions: >= 5.3.0, < 5.3.19, declared at pom.xml)
  - org.springframework:spring-context (versions: < 5.2.21.RELEASE, declared at pom.xml)

Recommended fix:
  - Upgrade org.springframework:spring-context to 5.3.19 or later
  - Upgrade org.springframework:spring-context to 5.2.21.RELEASE or later

### CVE-2021-43466: Template injection in thymeleaf-spring5
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-43466](https://github.com/advisories/GHSA-qcj6-jqrg-4wp2): Template injection in thymeleaf-spring5

Severity: CRITICAL

Affected dependencies:
  - org.thymeleaf:thymeleaf-spring5 (versions: <= 3.0.12.RELEASE, declared at pom.xml)

Recommended fix:
  - Upgrade org.thymeleaf:thymeleaf-spring5 to 3.0.13.RELEASE or later

### CVE-2025-41249: Spring Framework annotation detection mechanism may result in improper authorization
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-41249](https://github.com/advisories/GHSA-jmp9-x22r-554x): Spring Framework annotation detection mechanism may result in improper authorization

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-core (versions: >= 5.3.0, <= 5.3.44, declared at pom.xml)
  - org.springframework:spring-core (versions: >= 6.0.0, <= 6.1.22, declared at pom.xml)
  - org.springframework:spring-core (versions: >= 6.2.0, <= 6.2.10, declared at pom.xml)

Recommended fix:
  - Upgrade org.springframework:spring-core to 6.2.11 or later

### CVE-2025-52999: jackson-core can throw a StackoverflowError when processing deeply nested data
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-52999](https://github.com/advisories/GHSA-h46c-h94j-95f3): jackson-core can throw a StackoverflowError when processing deeply nested data

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-core (versions: < 2.15.0, declared at pom.xml)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-core to 2.15.0 or later

### CVE-2025-22228: Spring Security Does Not Enforce Password Length
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-22228](https://github.com/advisories/GHSA-mg83-c7gq-rv5c): Spring Security Does Not Enforce Password Length

Severity: HIGH

Affected dependencies:
  - org.springframework.security:spring-security-crypto (versions: >= 6.3.0, < 6.3.8, declared at pom.xml)
  - org.springframework.security:spring-security-crypto (versions: >= 6.4.0, < 6.4.4, declared at pom.xml)
  - org.springframework.security:spring-security-crypto (versions: >= 6.2.0, <= 6.2.9, declared at pom.xml)
  - org.springframework.security:spring-security-crypto (versions: >= 6.1.0, <= 6.1.13, declared at pom.xml)
  - org.springframework.security:spring-security-crypto (versions: >= 6.0.0, <= 6.0.15, declared at pom.xml)
  - org.springframework.security:spring-security-crypto (versions: >= 5.8.0, <= 5.8.17, declared at pom.xml)
  - org.springframework.security:spring-security-crypto (versions: <= 5.7.15, declared at pom.xml)

Recommended fix:
  - Upgrade org.springframework.security:spring-security-crypto to 6.3.8 or later
  - Upgrade org.springframework.security:spring-security-crypto to 6.4.4 or later
  - Upgrade org.springframework.security:spring-security-crypto to 6.2.10 or later
  - Upgrade org.springframework.security:spring-security-crypto to 6.1.14 or later
  - Upgrade org.springframework.security:spring-security-crypto to 6.0.16 or later
  - Upgrade org.springframework.security:spring-security-crypto to 5.8.18 or later
  - Upgrade org.springframework.security:spring-security-crypto to 5.7.16 or later

### CVE-2024-47072: XStream is vulnerable to a Denial of Service attack due to stack overflow from a manipulated binary input stream
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-47072](https://github.com/advisories/GHSA-hfq9-hggm-c56q): XStream is vulnerable to a Denial of Service attack due to stack overflow from a manipulated binary input stream

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream (versions: < 1.4.21, declared at pom.xml)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.21 or later

### CVE-2023-20863: Spring Framework vulnerable to denial of service
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2023-20863](https://github.com/advisories/GHSA-wxqc-pxw9-g2p8): Spring Framework vulnerable to denial of service

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-expression (versions: >= 6.0.0, < 6.0.8, declared at pom.xml)
  - org.springframework:spring-expression (versions: >= 5.3.0, < 5.3.27, declared at pom.xml)
  - org.springframework:spring-expression (versions: < 5.2.24.RELEASE, declared at pom.xml)

Recommended fix:
  - Upgrade org.springframework:spring-expression to 6.0.8 or later
  - Upgrade org.springframework:spring-expression to 5.3.27 or later
  - Upgrade org.springframework:spring-expression to 5.2.24.RELEASE or later

### CVE-2023-1436: Jettison vulnerable to infinite recursion
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2023-1436](https://github.com/advisories/GHSA-q6g2-g7f3-rr83): Jettison vulnerable to infinite recursion

Severity: HIGH

Affected dependencies:
  - org.codehaus.jettison:jettison (versions: < 1.5.4, declared at pom.xml)

Recommended fix:
  - Upgrade org.codehaus.jettison:jettison to 1.5.4 or later

### CVE-2022-40151: XStream can cause a Denial of Service by injecting deeply nested objects raising a stack overflow
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-40151](https://github.com/advisories/GHSA-f8cc-g7j8-xxpm): XStream can cause a Denial of Service by injecting deeply nested objects raising a stack overflow

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream (versions: < 1.4.20, declared at pom.xml)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.20 or later

### CVE-2022-41966: XStream can cause Denial of Service via stack overflow
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-41966](https://github.com/advisories/GHSA-j563-grx4-pjpv): XStream can cause Denial of Service via stack overflow

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream (versions: < 1.4.20, declared at pom.xml)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.20 or later

### CVE-2022-45693: Jettison Out-of-bounds Write vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-45693](https://github.com/advisories/GHSA-grr4-wv38-f68w): Jettison Out-of-bounds Write vulnerability

Severity: HIGH

Affected dependencies:
  - org.codehaus.jettison:jettison (versions: < 1.5.2, declared at pom.xml)

Recommended fix:
  - Upgrade org.codehaus.jettison:jettison to 1.5.2 or later

### CVE-2022-45685: Jettison Out-of-bounds Write vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-45685](https://github.com/advisories/GHSA-7rf3-mqpx-h7xg): Jettison Out-of-bounds Write vulnerability

Severity: HIGH

Affected dependencies:
  - org.codehaus.jettison:jettison (versions: < 1.5.2, declared at pom.xml)

Recommended fix:
  - Upgrade org.codehaus.jettison:jettison to 1.5.2 or later

### CVE-2022-40150: Jettison memory exhaustion
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-40150](https://github.com/advisories/GHSA-x27m-9w8j-5vcw): Jettison memory exhaustion

Severity: HIGH

Affected dependencies:
  - org.codehaus.jettison:jettison (versions: < 1.5.2, declared at pom.xml)

Recommended fix:
  - Upgrade org.codehaus.jettison:jettison to 1.5.2 or later

### CVE-2022-22965: Remote Code Execution in Spring Framework
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml, pom.xml:30

[CVE-2022-22965](https://github.com/advisories/GHSA-36p3-wjmg-h94x): Remote Code Execution in Spring Framework

Severity: CRITICAL

Affected dependencies:
  - org.springframework:spring-beans (versions: >= 5.3.0, < 5.3.18, declared at pom.xml)
  - org.springframework:spring-webmvc (versions: >= 5.3.0, < 5.3.18, declared at pom.xml)
  - org.springframework.boot:spring-boot-starter-web (versions: < 2.5.12, declared at pom.xml:30)
  - org.springframework.boot:spring-boot-starter-web (versions: >= 2.6.0, < 2.6.6, declared at pom.xml:30)
  - org.springframework:spring-webflux (versions: >= 5.3.0, < 5.3.18, declared at pom.xml)
  - org.springframework.boot:spring-boot-starter-webflux (versions: < 2.5.12, declared at pom.xml)
  - org.springframework.boot:spring-boot-starter-webflux (versions: >= 2.6.0, < 2.6.6, declared at pom.xml)
  - org.springframework:spring-beans (versions: < 5.2.20.RELEASE, declared at pom.xml)
  - org.springframework:spring-webmvc (versions: < 5.2.20.RELEASE, declared at pom.xml)
  - org.springframework:spring-webflux (versions: < 5.2.20.RELEASE, declared at pom.xml)

Recommended fix:
  - Upgrade org.springframework:spring-beans to 5.3.18 or later
  - Upgrade org.springframework:spring-webmvc to 5.3.18 or later
  - Upgrade org.springframework.boot:spring-boot-starter-web to 2.5.12 or later
  - Upgrade org.springframework.boot:spring-boot-starter-web to 2.6.6 or later
  - Upgrade org.springframework:spring-webflux to 5.3.18 or later
  - Upgrade org.springframework.boot:spring-boot-starter-webflux to 2.5.12 or later
  - Upgrade org.springframework.boot:spring-boot-starter-webflux to 2.6.6 or later
  - Upgrade org.springframework:spring-beans to 5.2.20.RELEASE or later
  - Upgrade org.springframework:spring-webmvc to 5.2.20.RELEASE or later
  - Upgrade org.springframework:spring-webflux to 5.2.20.RELEASE or later

### CVE-2021-43859: Denial of Service by injecting highly recursive collections or maps in XStream
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-43859](https://github.com/advisories/GHSA-rmr5-cpv2-vgjf): Denial of Service by injecting highly recursive collections or maps in XStream

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream (versions: < 1.4.19, declared at pom.xml)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.19 or later

### CVE-2021-39139: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-39139](https://github.com/advisories/GHSA-64xx-cq4q-mf44): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream (versions: < 1.4.18, declared at pom.xml)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39141: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-39141](https://github.com/advisories/GHSA-g5w6-mrj7-75h2): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream (versions: < 1.4.18, declared at pom.xml)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39144: XStream is vulnerable to a Remote Command Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-39144](https://github.com/advisories/GHSA-j9h8-phrw-h4fh): XStream is vulnerable to a Remote Command Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream (versions: < 1.4.18, declared at pom.xml)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39145: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-39145](https://github.com/advisories/GHSA-8jrj-525p-826v): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream (versions: < 1.4.18, declared at pom.xml)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39146: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-39146](https://github.com/advisories/GHSA-p8pq-r894-fm8f): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream (versions: < 1.4.18, declared at pom.xml)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39147: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-39147](https://github.com/advisories/GHSA-h7v4-7xg3-hxcc): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream (versions: < 1.4.18, declared at pom.xml)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39148: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-39148](https://github.com/advisories/GHSA-qrx8-8545-4wg2): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream (versions: < 1.4.18, declared at pom.xml)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39149: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-39149](https://github.com/advisories/GHSA-3ccq-5vw3-2p6x): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream (versions: < 1.4.18, declared at pom.xml)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39150: A Server-Side Forgery Request can be activated unmarshalling with XStream to access data streams from an arbitrary URL referencing a resource in an intranet or the local host
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-39150](https://github.com/advisories/GHSA-cxfm-5m4g-x7xp): A Server-Side Forgery Request can be activated unmarshalling with XStream to access data streams from an arbitrary URL referencing a resource in an intranet or the local host

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream (versions: < 1.4.18, declared at pom.xml)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39151: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-39151](https://github.com/advisories/GHSA-hph2-m3g5-xxv4): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream (versions: < 1.4.18, declared at pom.xml)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39152: A Server-Side Forgery Request can be activated unmarshalling with XStream to access data streams from an arbitrary URL referencing a resource in an intranet or the local host
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-39152](https://github.com/advisories/GHSA-xw4p-crpj-vjx2): A Server-Side Forgery Request can be activated unmarshalling with XStream to access data streams from an arbitrary URL referencing a resource in an intranet or the local host

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream (versions: < 1.4.18, declared at pom.xml)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39153: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-39153](https://github.com/advisories/GHSA-2q8x-2p7f-574v): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream (versions: < 1.4.18, declared at pom.xml)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39154: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-39154](https://github.com/advisories/GHSA-6w62-hx7r-mw68): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream (versions: < 1.4.18, declared at pom.xml)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-29505: XStream is vulnerable to a Remote Command Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-29505](https://github.com/advisories/GHSA-7chv-rrw6-w6fc): XStream is vulnerable to a Remote Command Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream (versions: < 1.4.17, declared at pom.xml)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.17 or later

### CVE-2021-21341: XStream can cause a Denial of Service.
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-21341](https://github.com/advisories/GHSA-2p3x-qw9c-25hh): XStream can cause a Denial of Service.

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream (versions: < 1.4.16, declared at pom.xml)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.16 or later

### CVE-2026-40973: Spring Boot accepts predictable temp directory without ownership verification
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml:16

[CVE-2026-40973](https://github.com/advisories/GHSA-wwpq-f5c3-7hvx): Spring Boot accepts predictable temp directory without ownership verification

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot (versions: >= 4.0.0, < 4.0.6, declared at pom.xml:16)
  - org.springframework.boot:spring-boot (versions: >= 3.5.0, < 3.5.14, declared at pom.xml:16)
  - org.springframework.boot:spring-boot (versions: >= 3.4.0, <= 3.4.15, declared at pom.xml:16)
  - org.springframework.boot:spring-boot (versions: >= 3.3.0, <= 3.3.18, declared at pom.xml:16)
  - org.springframework.boot:spring-boot (versions: <= 2.7.32, declared at pom.xml:16)

Recommended fix:
  - Upgrade org.springframework.boot:spring-boot to 4.0.6 or later
  - Upgrade org.springframework.boot:spring-boot to 3.5.14 or later

### CVE-2025-22235: Spring Boot EndpointRequest.to() creates wrong matcher if actuator endpoint is not exposed
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml:16

[CVE-2025-22235](https://github.com/advisories/GHSA-rc42-6c7j-7h5r): Spring Boot EndpointRequest.to() creates wrong matcher if actuator endpoint is not exposed

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot (versions: <= 2.7.24.2, declared at pom.xml:16)
  - org.springframework.boot:spring-boot (versions: >= 3.1.0, <= 3.1.15.2, declared at pom.xml:16)
  - org.springframework.boot:spring-boot (versions: >= 3.2.0, <= 3.2.13.2, declared at pom.xml:16)
  - org.springframework.boot:spring-boot (versions: >= 3.3.0, <= 3.3.10, declared at pom.xml:16)
  - org.springframework.boot:spring-boot (versions: >= 3.4.0, <= 3.4.4, declared at pom.xml:16)

Recommended fix:
  - Upgrade org.springframework.boot:spring-boot to 3.3.11 or later
  - Upgrade org.springframework.boot:spring-boot to 3.4.5 or later

### CVE-2024-22262: Spring Framework URL Parsing with Host Validation
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-22262](https://github.com/advisories/GHSA-2wrp-6fg6-hmc5): Spring Framework URL Parsing with Host Validation

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-web (versions: < 5.3.34, declared at pom.xml)
  - org.springframework:spring-web (versions: >= 6.0.0, < 6.0.19, declared at pom.xml)
  - org.springframework:spring-web (versions: >= 6.1.0, < 6.1.6, declared at pom.xml)

Recommended fix:
  - Upgrade org.springframework:spring-web to 5.3.34 or later
  - Upgrade org.springframework:spring-web to 6.0.19 or later
  - Upgrade org.springframework:spring-web to 6.1.6 or later

### CVE-2024-22259: Spring Framework URL Parsing with Host Validation Vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-22259](https://github.com/advisories/GHSA-hgjh-9rj2-g67j): Spring Framework URL Parsing with Host Validation Vulnerability

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-web (versions: >= 6.1.0, < 6.1.5, declared at pom.xml)
  - org.springframework:spring-web (versions: >= 6.0.0, < 6.0.18, declared at pom.xml)
  - org.springframework:spring-web (versions: < 5.3.33, declared at pom.xml)

Recommended fix:
  - Upgrade org.springframework:spring-web to 6.1.5 or later
  - Upgrade org.springframework:spring-web to 6.0.18 or later
  - Upgrade org.springframework:spring-web to 5.3.33 or later

### CVE-2024-22243: Spring Web vulnerable to Open Redirect or Server Side Request Forgery
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-22243](https://github.com/advisories/GHSA-ccgv-vj62-xf9h): Spring Web vulnerable to Open Redirect or Server Side Request Forgery

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-web (versions: >= 6.1.0, < 6.1.4, declared at pom.xml)
  - org.springframework:spring-web (versions: >= 6.0.0, < 6.0.17, declared at pom.xml)
  - org.springframework:spring-web (versions: >= 5.3.0, < 5.3.32, declared at pom.xml)
  - org.springframework:spring-web (versions: <= 5.2.25.RELEASE, declared at pom.xml)

Recommended fix:
  - Upgrade org.springframework:spring-web to 6.1.4 or later
  - Upgrade org.springframework:spring-web to 6.0.17 or later
  - Upgrade org.springframework:spring-web to 5.3.32 or later

### CVE-2023-1370: json-smart Uncontrolled Recursion vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2023-1370](https://github.com/advisories/GHSA-493p-pfq6-5258): json-smart Uncontrolled Recursion vulnerability

Severity: HIGH

Affected dependencies:
  - net.minidev:json-smart (versions: < 2.4.9, declared at pom.xml)

Recommended fix:
  - Upgrade net.minidev:json-smart to 2.4.9 or later

### CVE-2021-22118: Improper Privilege Management in Spring Framework
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-22118](https://github.com/advisories/GHSA-gfwj-fwqj-fp3v): Improper Privilege Management in Spring Framework

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-web (versions: >= 5.2.0, <= 5.2.14, declared at pom.xml)
  - org.springframework:spring-web (versions: >= 5.3.0, <= 5.3.6, declared at pom.xml)

Recommended fix:
  - Upgrade org.springframework:spring-web to 5.2.15 or later
  - Upgrade org.springframework:spring-web to 5.3.7 or later

### CVE-2016-1000027: Pivotal Spring Framework contains unsafe Java deserialization methods
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2016-1000027](https://github.com/advisories/GHSA-4wrc-f8pq-fpqp): Pivotal Spring Framework contains unsafe Java deserialization methods

Severity: CRITICAL

Affected dependencies:
  - org.springframework:spring-web (versions: < 6.0.0, declared at pom.xml)

Recommended fix:
  - Upgrade org.springframework:spring-web to 6.0.0 or later

### CVE-2026-22733: Spring Boot has an Authentication Bypass under Actuator CloudFoundry endpoints
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-22733](https://github.com/advisories/GHSA-mgvc-8q2h-5pgc): Spring Boot has an Authentication Bypass under Actuator CloudFoundry endpoints

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot-starter-actuator (versions: >= 4.0.0-M1, < 4.0.4, declared at pom.xml)
  - org.springframework.boot:spring-boot-starter-actuator (versions: >= 3.5.0, < 3.5.12, declared at pom.xml)
  - org.springframework.boot:spring-boot-starter-actuator (versions: >= 3.4.0, <= 3.4.13, declared at pom.xml)
  - org.springframework.boot:spring-boot-starter-actuator (versions: >= 3.0.0, <= 3.3.13, declared at pom.xml)
  - org.springframework.boot:spring-boot-starter-actuator (versions: <= 2.7.18, declared at pom.xml)

Recommended fix:
  - Upgrade org.springframework.boot:spring-boot-starter-actuator to 4.0.4 or later
  - Upgrade org.springframework.boot:spring-boot-starter-actuator to 3.5.12 or later

### CVE-2024-38819: Spring Framework Path Traversal vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-38819](https://github.com/advisories/GHSA-g5vr-rgqm-vf78): Spring Framework Path Traversal vulnerability

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-webflux (versions: >= 6.1.0, < 6.1.14, declared at pom.xml)
  - org.springframework:spring-webmvc (versions: >= 6.1.0, < 6.1.14, declared at pom.xml)
  - org.springframework:spring-webflux (versions: <= 5.3.39, declared at pom.xml)
  - org.springframework:spring-webmvc (versions: <= 5.3.39, declared at pom.xml)
  - org.springframework:spring-webflux (versions: >= 6.0.0, <= 6.0.23, declared at pom.xml)
  - org.springframework:spring-webmvc (versions: >= 6.0.0, <= 6.0.23, declared at pom.xml)

Recommended fix:
  - Upgrade org.springframework:spring-webflux to 6.1.14 or later
  - Upgrade org.springframework:spring-webmvc to 6.1.14 or later

### CVE-2024-38816: Path traversal vulnerability in functional web frameworks
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-38816](https://github.com/advisories/GHSA-cx7f-g6mp-7hqm): Path traversal vulnerability in functional web frameworks

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-webmvc (versions: >= 6.1.0, < 6.1.13, declared at pom.xml)
  - org.springframework:spring-webflux (versions: >= 6.1.0, < 6.1.13, declared at pom.xml)
  - org.springframework:spring-webmvc (versions: >= 6.0.0, <= 6.0.23, declared at pom.xml)
  - org.springframework:spring-webflux (versions: >= 6.0.0, <= 6.0.23, declared at pom.xml)
  - org.springframework:spring-webmvc (versions: >= 5.3.0, <= 5.3.39, declared at pom.xml)
  - org.springframework:spring-webflux (versions: >= 5.3.0, <= 5.3.39, declared at pom.xml)

Recommended fix:
  - Upgrade org.springframework:spring-webmvc to 6.1.13 or later
  - Upgrade org.springframework:spring-webflux to 6.1.13 or later

### CVE-2023-20860: Spring Framework is vulnerable to security bypass via mvcRequestMatcher pattern mismatch
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml, pom.xml:4

[CVE-2023-20860](https://github.com/advisories/GHSA-7phw-cxx7-q9vq): Spring Framework is vulnerable to security bypass via mvcRequestMatcher pattern mismatch

Severity: CRITICAL

Affected dependencies:
  - org.springframework:spring (versions: >= 6.0.0, < 6.0.7, declared at pom.xml:4)
  - org.springframework:spring (versions: >= 5.3.0, < 5.3.26, declared at pom.xml:4)
  - org.springframework:spring-webmvc (versions: >= 6.0.0, < 6.0.7, declared at pom.xml)
  - org.springframework:spring-webmvc (versions: >= 5.3.0, < 5.3.26, declared at pom.xml)

Recommended fix:
  - Upgrade org.springframework:spring to 6.0.7 or later
  - Upgrade org.springframework:spring to 5.3.26 or later
  - Upgrade org.springframework:spring-webmvc to 6.0.7 or later
  - Upgrade org.springframework:spring-webmvc to 5.3.26 or later

### CVE-2022-1471: SnakeYaml Constructor Deserialization Remote Code Execution
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-1471](https://github.com/advisories/GHSA-mjmj-j48q-9wg2): SnakeYaml Constructor Deserialization Remote Code Execution

Severity: HIGH

Affected dependencies:
  - org.yaml:snakeyaml (versions: <= 1.33, declared at pom.xml)

Recommended fix:
  - Upgrade org.yaml:snakeyaml to 2.0 or later

### CVE-2022-41853: HyperSQL DataBase vulnerable to remote code execution when processing untrusted input
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml:58

[CVE-2022-41853](https://github.com/advisories/GHSA-77xx-rxvh-q682): HyperSQL DataBase vulnerable to remote code execution when processing untrusted input

Severity: CRITICAL

Affected dependencies:
  - org.hsqldb:hsqldb (versions: < 2.7.1, declared at pom.xml:58)

Recommended fix:
  - Upgrade org.hsqldb:hsqldb to 2.7.1 or later

### CVE-2022-25857: Uncontrolled Resource Consumption in snakeyaml
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-25857](https://github.com/advisories/GHSA-3mc7-4q67-w48m): Uncontrolled Resource Consumption in snakeyaml

Severity: HIGH

Affected dependencies:
  - org.yaml:snakeyaml (versions: < 1.31, declared at pom.xml)

Recommended fix:
  - Upgrade org.yaml:snakeyaml to 1.31 or later

### CVE-2022-22970: Denial of service in Spring Framework
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-22970](https://github.com/advisories/GHSA-hh26-6xwr-ggv7): Denial of service in Spring Framework

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-beans (versions: <= 5.2.21.RELEASE, declared at pom.xml)
  - org.springframework:spring-beans (versions: >= 5.3.0, < 5.3.20, declared at pom.xml)

Recommended fix:
  - Upgrade org.springframework:spring-beans to 5.2.22.RELEASE or later
  - Upgrade org.springframework:spring-beans to 5.3.20 or later

### CVE-2026-41284: Apache Tomcat: Unbounded read in WebDAV LOCK and  PROPFIND handling
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-41284](https://github.com/advisories/GHSA-gx5v-xp9w-j4cg): Apache Tomcat: Unbounded read in WebDAV LOCK and  PROPFIND handling

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core (versions: < 9.0.118, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, < 10.1.55, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 11.0.0-M1, < 11.0.22, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: < 9.0.118, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: >= 10.1.0-M1, < 10.1.55, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: >= 11.0.0-M1, < 11.0.22, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: < 9.0.118, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 10.1.0-M1, < 10.1.55, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 11.0.0-M1, < 11.0.22, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.22 or later
  - Upgrade org.apache.tomcat:tomcat to 9.0.118 or later
  - Upgrade org.apache.tomcat:tomcat to 10.1.55 or later
  - Upgrade org.apache.tomcat:tomcat to 11.0.22 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 9.0.118 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 10.1.55 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 11.0.22 or later

### CVE-2026-43512: Apache Tomcat - Digest authenticator will authenticate any unknown user
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-43512](https://github.com/advisories/GHSA-h6fc-48rj-7qqh): Apache Tomcat - Digest authenticator will authenticate any unknown user

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core (versions: < 9.0.118, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, < 10.1.55, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 11.0.0-M1, < 11.0.22, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: < 9.0.118, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: >= 10.1.0-M1, < 10.1.55, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: >= 11.0.0-M1, < 11.0.22, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: < 9.0.118, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 10.1.0-M1, < 10.1.55, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 11.0.0-M1, < 11.0.22, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.22 or later
  - Upgrade org.apache.tomcat:tomcat to 9.0.118 or later
  - Upgrade org.apache.tomcat:tomcat to 10.1.55 or later
  - Upgrade org.apache.tomcat:tomcat to 11.0.22 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 9.0.118 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 10.1.55 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 11.0.22 or later

### CVE-2026-43513: Apache Tomcat: LockOutRealm treats user names as case-sensitive
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-43513](https://github.com/advisories/GHSA-5mp6-jrq3-r938): Apache Tomcat: LockOutRealm treats user names as case-sensitive

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core (versions: < 9.0.118, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, < 10.1.55, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 11.0.0-M1, < 11.0.22, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: < 9.0.118, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: >= 10.1.0-M1, < 10.1.55, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: >= 11.0.0-M1, < 11.0.22, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: < 9.0.118, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 10.1.0-M1, < 10.1.55, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 11.0.0-M1, < 11.0.22, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.22 or later
  - Upgrade org.apache.tomcat:tomcat to 9.0.118 or later
  - Upgrade org.apache.tomcat:tomcat to 10.1.55 or later
  - Upgrade org.apache.tomcat:tomcat to 11.0.22 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 9.0.118 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 10.1.55 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 11.0.22 or later

### CVE-2026-43515: Apache Tomcat - Security constraints not correctly applied
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-43515](https://github.com/advisories/GHSA-5m62-pw8w-7w9f): Apache Tomcat - Security constraints not correctly applied

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core (versions: < 9.0.118, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, < 10.1.55, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 11.0.0-M1, < 11.0.22, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: < 9.0.118, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: >= 10.1.0-M1, < 10.1.55, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: >= 11.0.0-M1, < 11.0.22, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: < 9.0.118, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 10.1.0-M1, < 10.1.55, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 11.0.0-M1, < 11.0.22, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.22 or later
  - Upgrade org.apache.tomcat:tomcat to 9.0.118 or later
  - Upgrade org.apache.tomcat:tomcat to 10.1.55 or later
  - Upgrade org.apache.tomcat:tomcat to 11.0.22 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 9.0.118 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 10.1.55 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 11.0.22 or later

### CVE-2026-41293: Apache Tomcat - HTTP/2 request headers not validated
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-41293](https://github.com/advisories/GHSA-r29c-68gh-xp6x): Apache Tomcat - HTTP/2 request headers not validated

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core (versions: < 9.0.118, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, < 10.1.55, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 11.0.0-M1, < 11.0.22, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: < 9.0.118, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: >= 10.1.0-M1, < 10.1.55, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: >= 11.0.0-M1, < 11.0.22, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: < 9.0.118, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 10.1.0-M1, < 10.1.55, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 11.0.0-M1, < 11.0.22, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.22 or later
  - Upgrade org.apache.tomcat:tomcat to 9.0.118 or later
  - Upgrade org.apache.tomcat:tomcat to 10.1.55 or later
  - Upgrade org.apache.tomcat:tomcat to 11.0.22 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 9.0.118 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 10.1.55 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 11.0.22 or later

### CVE-2026-42498: Apache Tomcat - WebSocket authentication header exposure
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-42498](https://github.com/advisories/GHSA-fv25-8xcx-gqjc): Apache Tomcat - WebSocket authentication header exposure

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core (versions: < 9.0.118, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, < 10.1.55, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 11.0.0-M1, < 11.0.22, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: < 9.0.118, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: >= 10.1.0-M1, < 10.1.55, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: >= 11.0.0-M1, < 11.0.22, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: < 9.0.118, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 10.1.0-M1, < 10.1.55, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 11.0.0-M1, < 11.0.22, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.22 or later
  - Upgrade org.apache.tomcat:tomcat to 9.0.118 or later
  - Upgrade org.apache.tomcat:tomcat to 10.1.55 or later
  - Upgrade org.apache.tomcat:tomcat to 11.0.22 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 9.0.118 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 10.1.55 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 11.0.22 or later

### CVE-2026-34483: Apache Tomcat has an Improper Encoding or Escaping of Output vulnerability in the JsonAccessLogValve
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-34483](https://github.com/advisories/GHSA-rv64-5gf8-9qq8): Apache Tomcat has an Improper Encoding or Escaping of Output vulnerability in the JsonAccessLogValve

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat-catalina (versions: >= 9.0.40, < 9.0.116, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 10.1.0-M1, < 10.1.54, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 11.0.0-M1, < 11.0.21, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: >= 9.0.40, < 9.0.116, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: >= 10.1.0-M1, < 10.1.54, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: >= 11.0.0-M1, < 11.0.21, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 9.0.40, < 9.0.116, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, < 10.1.54, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 11.0.0-M1, < 11.0.21, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat:tomcat-catalina to 9.0.116 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 10.1.54 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 11.0.21 or later
  - Upgrade org.apache.tomcat:tomcat to 9.0.116 or later
  - Upgrade org.apache.tomcat:tomcat to 10.1.54 or later
  - Upgrade org.apache.tomcat:tomcat to 11.0.21 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.116 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.54 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.21 or later

### CVE-2026-24880: Apache Tomcat has an HTTP Request/Response Smuggling vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-24880](https://github.com/advisories/GHSA-563x-q5rq-57qp): Apache Tomcat has an HTTP Request/Response Smuggling vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat-coyote (versions: >= 7.0.0, < 9.0.116, declared at pom.xml)
  - org.apache.tomcat:tomcat-coyote (versions: >= 10.1.0-M1, < 10.1.52, declared at pom.xml)
  - org.apache.tomcat:tomcat-coyote (versions: >= 11.0.0-M1, <= 11.0.18, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 7.0.0, < 9.0.116, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, < 10.1.52, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 11.0.0-M1, <= 11.0.18, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat:tomcat-coyote to 9.0.116 or later
  - Upgrade org.apache.tomcat:tomcat-coyote to 10.1.52 or later
  - Upgrade org.apache.tomcat:tomcat-coyote to 11.0.20 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.116 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.52 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.20 or later

### CVE-2026-24400: AssertJ has XML External Entity (XXE) vulnerability when parsing untrusted XML via isXmlEqualTo assertion
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-24400](https://github.com/advisories/GHSA-rqfh-9r24-8c9r): AssertJ has XML External Entity (XXE) vulnerability when parsing untrusted XML via isXmlEqualTo assertion

Severity: HIGH

Affected dependencies:
  - org.assertj:assertj-core (versions: >= 1.4.0, <= 3.27.6, declared at pom.xml)

Recommended fix:
  - Upgrade org.assertj:assertj-core to 3.27.7 or later

### CVE-2026-0603: Hibernate vulnerable to SQL Injection
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-0603](https://github.com/advisories/GHSA-2p5w-cvg5-gc5c): Hibernate vulnerable to SQL Injection

Severity: HIGH

Affected dependencies:
  - org.hibernate:hibernate-core (versions: >= 5.2.8, <= 5.6.15, declared at pom.xml)

### CVE-2025-55752: Apache Tomcat Vulnerable to Relative Path Traversal
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-55752](https://github.com/advisories/GHSA-wmwf-9ccg-fff5): Apache Tomcat Vulnerable to Relative Path Traversal

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat (versions: >= 11.0.0-M1, < 11.0.11, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: >= 10.1.0-M1, < 10.1.45, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 11.0.0-M1, < 11.0.11, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 10.1.0-M1, < 10.1.45, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 11.0.0-M1, < 11.0.11, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, < 10.1.45, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: >= 9.0.0-M11, < 9.0.109, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 9.0.0-M11, < 9.0.109, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 9.0.0-M11, < 9.0.109, declared at pom.xml)
  - org.apache.tomcat:tomcat (versions: >= 8.5.6, <= 8.5.100, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 8.5.6, <= 8.5.100, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 8.5.6, <= 8.5.100, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat:tomcat to 11.0.11 or later
  - Upgrade org.apache.tomcat:tomcat to 10.1.45 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 11.0.11 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 10.1.45 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.11 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.45 or later
  - Upgrade org.apache.tomcat:tomcat to 9.0.109 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 9.0.109 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.109 or later

### CVE-2025-48989: Apache Tomcat Improper Resource Shutdown or Release vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-48989](https://github.com/advisories/GHSA-gqp3-2cvr-x8m3): Apache Tomcat Improper Resource Shutdown or Release vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat-coyote (versions: >= 11.0.0-M1, < 11.0.10, declared at pom.xml)
  - org.apache.tomcat:tomcat-coyote (versions: >= 10.1.0-M1, < 10.1.44, declared at pom.xml)
  - org.apache.tomcat:tomcat-coyote (versions: >= 9.0.0.M1, < 9.0.108, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 11.0.0-M1, < 11.0.10, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, < 10.1.44, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 9.0.0.M1, < 9.0.108, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat:tomcat-coyote to 11.0.10 or later
  - Upgrade org.apache.tomcat:tomcat-coyote to 10.1.44 or later
  - Upgrade org.apache.tomcat:tomcat-coyote to 9.0.108 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.10 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.44 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.108 or later

### CVE-2025-53506: Apache Tomcat Coyote vulnerable to Denial of Service via excessive HTTP/2 streams
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-53506](https://github.com/advisories/GHSA-25xr-qj8w-c4vf): Apache Tomcat Coyote vulnerable to Denial of Service via excessive HTTP/2 streams

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat-coyote (versions: >= 11.0.0-M1, < 11.0.9, declared at pom.xml)
  - org.apache.tomcat:tomcat-coyote (versions: >= 10.1.0-M1, < 10.1.43, declared at pom.xml)
  - org.apache.tomcat:tomcat-coyote (versions: >= 9.0.0.M1, < 9.0.107, declared at pom.xml)
  - org.apache.tomcat:tomcat-coyote (versions: >= 8.5.0, <= 8.5.100, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 8.5.0, <= 8.5.100, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 9.0.0.M1, < 9.0.107, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, < 10.1.43, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 11.0.0-M1, < 11.0.9, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat:tomcat-coyote to 11.0.9 or later
  - Upgrade org.apache.tomcat:tomcat-coyote to 10.1.43 or later
  - Upgrade org.apache.tomcat:tomcat-coyote to 9.0.107 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.107 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.43 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.9 or later

### CVE-2025-52520: Apache Tomcat Catalina is vulnerable to DoS attack through bypassing of size limits
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-52520](https://github.com/advisories/GHSA-wr62-c79q-cv37): Apache Tomcat Catalina is vulnerable to DoS attack through bypassing of size limits

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat-catalina (versions: >= 11.0.0-M1, < 11.0.9, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 10.1.0-M1, < 10.1.43, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 9.0.0.M1, < 9.0.107, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 8.5.0, <= 8.5.100, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 11.0.0-M1, < 11.0.9, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, < 10.1.43, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 9.0.0.M1, < 9.0.107, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 8.5.0, <= 8.5.100, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat:tomcat-catalina to 11.0.9 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 10.1.43 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 9.0.107 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.9 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.43 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.107 or later

### CVE-2025-48988: Apache Tomcat - DoS in multipart upload
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-48988](https://github.com/advisories/GHSA-h3gc-qfqq-6h8f): Apache Tomcat - DoS in multipart upload

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat-catalina (versions: >= 11.0.0-M1, <= 11.0.7, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 10.1.0-M1, <= 10.1.41, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 9.0.0.M1, <= 9.0.105, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 11.0.0-M1, <= 11.0.7, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, <= 10.1.41, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 9.0.0.M1, <= 9.0.105, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 8.5.0, <= 8.5.100, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 8.5.0, <= 8.5.100, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat:tomcat-catalina to 11.0.8 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 10.1.42 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 9.0.106 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.8 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.42 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.106 or later

### CVE-2025-24813: Apache Tomcat: Potential RCE and/or information disclosure and/or information corruption with partial PUT
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-24813](https://github.com/advisories/GHSA-83qj-6fr2-vhqg): Apache Tomcat: Potential RCE and/or information disclosure and/or information corruption with partial PUT

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat:tomcat-catalina (versions: >= 11.0.0-M1, < 11.0.3, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 10.1.0-M1, < 10.1.35, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 9.0.0.M1, < 9.0.99, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 11.0.0-M1, < 11.0.3, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, < 10.1.35, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 9.0.0.M1, < 9.0.99, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 8.5.0, <= 8.5.100, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 8.5.0, <= 8.5.100, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat:tomcat-catalina to 11.0.3 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 10.1.35 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 9.0.99 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.3 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.35 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.99 or later

### CVE-2024-56337: Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-56337](https://github.com/advisories/GHSA-27hp-xhwr-wr2m): Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat-catalina (versions: >= 11.0.0-M1, < 11.0.2, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 10.1.0-M1, < 10.1.34, declared at pom.xml)
  - org.apache.tomcat:tomcat-embed-core (versions: >= 9.0.0.M1, < 9.0.98, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 11.0.0-M1, < 11.0.2, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, < 10.1.34, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 9.0.0.M1, < 9.0.98, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat:tomcat-catalina to 11.0.2 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 10.1.34 or later
  - Upgrade org.apache.tomcat:tomcat-embed-core to 9.0.98 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.2 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.34 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.98 or later

### CVE-2024-50379: Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-50379](https://github.com/advisories/GHSA-5j33-cvvr-w245): Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat-catalina (versions: >= 11.0.0-M1, < 11.0.2, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 10.1.0-M1, < 10.1.34, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 9.0.0.M1, < 9.0.98, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 11.0.0-M1, < 11.0.2, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, < 10.1.34, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 9.0.0.M1, < 9.0.98, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 8.5.0, <= 8.5.100, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 8.5.0, <= 8.5.100, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat:tomcat-catalina to 11.0.2 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 10.1.34 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 9.0.98 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.2 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.34 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.98 or later

### CVE-2024-34750: Apache Tomcat - Denial of Service
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-34750](https://github.com/advisories/GHSA-wm9w-rjj3-j356): Apache Tomcat - Denial of Service

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 11.0.0-M1, < 11.0.0-M21, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, < 10.1.25, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 9.0.0-M1, < 9.0.90, declared at pom.xml)
  - org.apache.tomcat:tomcat-coyote (versions: >= 11.0.0-M1, < 11.0.0-M21, declared at pom.xml)
  - org.apache.tomcat:tomcat-coyote (versions: >= 10.1.0-M1, < 10.1.25, declared at pom.xml)
  - org.apache.tomcat:tomcat-coyote (versions: >= 9.0.0-M1, < 9.0.90, declared at pom.xml)
  - org.apache.tomcat:tomcat-coyote (versions: >= 8.5.0, <= 8.5.100, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 8.5.0, <= 8.5.100, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.0-M21 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.25 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.90 or later
  - Upgrade org.apache.tomcat:tomcat-coyote to 11.0.0-M21 or later
  - Upgrade org.apache.tomcat:tomcat-coyote to 10.1.25 or later
  - Upgrade org.apache.tomcat:tomcat-coyote to 9.0.90 or later

### CVE-2023-6378: logback serialization vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2023-6378](https://github.com/advisories/GHSA-vmq6-5m68-f53m): logback serialization vulnerability

Severity: HIGH

Affected dependencies:
  - ch.qos.logback:logback-classic (versions: >= 1.4.0, < 1.4.12, declared at pom.xml)
  - ch.qos.logback:logback-core (versions: >= 1.4.0, < 1.4.12, declared at pom.xml)
  - ch.qos.logback:logback-classic (versions: >= 1.3.0, < 1.3.12, declared at pom.xml)
  - ch.qos.logback:logback-core (versions: >= 1.3.0, < 1.3.12, declared at pom.xml)
  - ch.qos.logback:logback-core (versions: < 1.2.13, declared at pom.xml)
  - ch.qos.logback:logback-classic (versions: < 1.2.13, declared at pom.xml)

Recommended fix:
  - Upgrade ch.qos.logback:logback-classic to 1.4.12 or later
  - Upgrade ch.qos.logback:logback-core to 1.4.12 or later
  - Upgrade ch.qos.logback:logback-classic to 1.3.12 or later
  - Upgrade ch.qos.logback:logback-core to 1.3.12 or later
  - Upgrade ch.qos.logback:logback-core to 1.2.13 or later
  - Upgrade ch.qos.logback:logback-classic to 1.2.13 or later

### CVE-2023-46589: Apache Tomcat Improper Input Validation vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2023-46589](https://github.com/advisories/GHSA-fccv-jmmp-qg76): Apache Tomcat Improper Input Validation vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat-catalina (versions: >= 11.0.0-M1, < 11.0.0-M11, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 10.1.0-M1, < 10.1.16, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 9.0.0-M1, < 9.0.83, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 8.5.0, < 8.5.96, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 11.0.0-M1, < 11.0.0-M11, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, < 10.1.16, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 9.0.0-M1, < 9.0.83, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 8.5.0, < 8.5.96, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat:tomcat-catalina to 11.0.0-M11 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 10.1.16 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 9.0.83 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 8.5.96 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.0-M11 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.16 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.83 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.96 or later

### CVE-2023-20873: Spring Boot Security Bypass with Wildcard Pattern Matching on Cloud Foundry
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2023-20873](https://github.com/advisories/GHSA-g5h3-w546-pj7f): Spring Boot Security Bypass with Wildcard Pattern Matching on Cloud Foundry

Severity: CRITICAL

Affected dependencies:
  - org.springframework.boot:spring-boot-actuator-autoconfigure (versions: >= 3.0.0, < 3.0.6, declared at pom.xml)
  - org.springframework.boot:spring-boot-actuator-autoconfigure (versions: >= 2.7.0, < 2.7.11, declared at pom.xml)
  - org.springframework.boot:spring-boot-actuator-autoconfigure (versions: >= 2.6.0, < 2.6.15, declared at pom.xml)
  - org.springframework.boot:spring-boot-actuator-autoconfigure (versions: < 2.5.15, declared at pom.xml)

Recommended fix:
  - Upgrade org.springframework.boot:spring-boot-actuator-autoconfigure to 3.0.6 or later
  - Upgrade org.springframework.boot:spring-boot-actuator-autoconfigure to 2.7.11 or later
  - Upgrade org.springframework.boot:spring-boot-actuator-autoconfigure to 2.6.15 or later
  - Upgrade org.springframework.boot:spring-boot-actuator-autoconfigure to 2.5.15 or later

### CVE-2021-46877: jackson-databind possible Denial of Service if using JDK serialization to serialize JsonNode
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-46877](https://github.com/advisories/GHSA-3x8x-79m2-3w2w): jackson-databind possible Denial of Service if using JDK serialization to serialize JsonNode

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind (versions: >= 2.10.0, < 2.12.6, declared at pom.xml)
  - com.fasterxml.jackson.core:jackson-databind (versions: >= 2.13.0, < 2.13.1, declared at pom.xml)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.12.6 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.13.1 or later

### CVE-2023-24998: Apache Commons FileUpload denial of service vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2023-24998](https://github.com/advisories/GHSA-hfrx-6qgj-fp6c): Apache Commons FileUpload denial of service vulnerability

Severity: HIGH

Affected dependencies:
  - commons-fileupload:commons-fileupload (versions: < 1.5, declared at pom.xml)
  - org.apache.tomcat:tomcat-coyote (versions: >= 10.1.0-M1, < 10.1.5, declared at pom.xml)
  - org.apache.tomcat:tomcat-coyote (versions: >= 11.0.0-M2, < 11.0.0-M5, declared at pom.xml)
  - org.apache.tomcat:tomcat-coyote (versions: >= 8.5.85, < 8.5.88, declared at pom.xml)
  - org.apache.tomcat:tomcat-coyote (versions: >= 9.0.0-M1, < 9.0.71, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, < 10.1.5, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 11.0.0-M2, < 11.0.0-M5, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 8.5.85, < 8.5.88, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 9.0.0-M1, < 9.0.71, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 10.1.0-M1, < 10.1.5, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 11.0.0-M2, < 11.0.0-M5, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 8.5.85, < 8.5.88, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 9.0.0-M1, < 9.0.71, declared at pom.xml)

Recommended fix:
  - Upgrade commons-fileupload:commons-fileupload to 1.5 or later
  - Upgrade org.apache.tomcat:tomcat-coyote to 10.1.5 or later
  - Upgrade org.apache.tomcat:tomcat-coyote to 11.0.0-M5 or later
  - Upgrade org.apache.tomcat:tomcat-coyote to 8.5.88 or later
  - Upgrade org.apache.tomcat:tomcat-coyote to 9.0.71 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.5 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.0-M5 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.88 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.71 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 10.1.5 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 11.0.0-M5 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 8.5.88 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 9.0.71 or later

### CVE-2022-45143: Apache Tomcat improperly escapes input from JsonErrorReportValve
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-45143](https://github.com/advisories/GHSA-rq2w-37h9-vg94): Apache Tomcat improperly escapes input from JsonErrorReportValve

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core (versions: = 8.5.83, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 9.0.40, <= 9.0.68, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0, <= 10.1.1, declared at pom.xml)
  - org.apache.tomcat:tomcat-catalina (versions: >= 10.1.0, <= 10.1.1, declared at pom.xml)
  - org.apache.tomcat:tomcat-util (versions: = 8.5.83, declared at pom.xml)
  - org.apache.tomcat:tomcat-util (versions: >= 9.0.40, < 9.0.69, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.84 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.69 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.2 or later
  - Upgrade org.apache.tomcat:tomcat-catalina to 10.1.2 or later
  - Upgrade org.apache.tomcat:tomcat-util to 8.5.84 or later
  - Upgrade org.apache.tomcat:tomcat-util to 9.0.69 or later

### CVE-2022-42252: Apache Tomcat may reject request containing invalid Content-Length header
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-42252](https://github.com/advisories/GHSA-p22x-g9px-3945): Apache Tomcat may reject request containing invalid Content-Length header

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 8.5.0, < 8.5.83, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 9.0.0-M1, < 9.0.68, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.0.0-M1, < 10.0.27, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.1.0-M1, < 10.1.1, declared at pom.xml)
  - org.apache.tomcat:tomcat-coyote (versions: >= 9.0.0-M1, < 9.0.68, declared at pom.xml)
  - org.apache.tomcat:tomcat-coyote (versions: >= 10.0.0-M1, < 10.0.27, declared at pom.xml)
  - org.apache.tomcat:tomcat-coyote (versions: >= 10.1.0-M1, < 10.1.1, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.83 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.68 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.0.27 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.1 or later
  - Upgrade org.apache.tomcat:tomcat-coyote to 9.0.68 or later
  - Upgrade org.apache.tomcat:tomcat-coyote to 10.0.27 or later
  - Upgrade org.apache.tomcat:tomcat-coyote to 10.1.1 or later

### CVE-2022-42003: Uncontrolled Resource Consumption in Jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-42003](https://github.com/advisories/GHSA-jjjh-jjxp-wpff): Uncontrolled Resource Consumption in Jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind (versions: >= 2.4.0-rc1, < 2.12.7.1, declared at pom.xml)
  - com.fasterxml.jackson.core:jackson-databind (versions: >= 2.13.0, < 2.13.4.2, declared at pom.xml)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.12.7.1 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.13.4.2 or later

### CVE-2022-42004: Uncontrolled Resource Consumption in FasterXML jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-42004](https://github.com/advisories/GHSA-rgv9-q543-rqg4): Uncontrolled Resource Consumption in FasterXML jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind (versions: >= 2.13.0, < 2.13.4, declared at pom.xml)
  - com.fasterxml.jackson.core:jackson-databind (versions: >= 2.4.0-rc1, < 2.12.7.1, declared at pom.xml)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.13.4 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.12.7.1 or later

### CVE-2022-25647: Deserialization of Untrusted Data in Gson
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-25647](https://github.com/advisories/GHSA-4jrv-ppp4-jm57): Deserialization of Untrusted Data in Gson

Severity: HIGH

Affected dependencies:
  - com.google.code.gson:gson (versions: < 2.8.9, declared at pom.xml)

Recommended fix:
  - Upgrade com.google.code.gson:gson to 2.8.9 or later

### CVE-2020-36518: Deeply nested json in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2020-36518](https://github.com/advisories/GHSA-57j2-w4cx-62h2): Deeply nested json in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind (versions: >= 2.13.0, <= 2.13.2.0, declared at pom.xml)
  - com.fasterxml.jackson.core:jackson-databind (versions: <= 2.12.6.0, declared at pom.xml)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.13.2.1 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.12.6.1 or later

### CVE-2021-25122: Exposure of Sensitive Information to an Unauthorized Actor in Apache Tomcat
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2021-25122](https://github.com/advisories/GHSA-j39c-c8hj-x4j3): Exposure of Sensitive Information to an Unauthorized Actor in Apache Tomcat

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 8.5.0, < 8.5.63, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 10.0.0-M1, < 10.0.2, declared at pom.xml)
  - org.apache.tomcat.embed:tomcat-embed-core (versions: >= 9.0.0-M1, < 9.0.43, declared at pom.xml)
  - org.apache.tomcat:tomcat-coyote (versions: >= 10.0.0-M1, < 10.0.2, declared at pom.xml)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.63 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.0.2 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.43 or later
  - Upgrade org.apache.tomcat:tomcat-coyote to 10.0.2 or later

## CWE Findings (Code-Level Vulnerabilities)

### CWE-477: Use of Obsolete Function
- **Category:** Code Quality
- **Severity:** optional
- **Story Points:** 1
- **Files:** src/main/java/io/pivotal/microservices/accounts/AccountsController.java, src/main/java/io/pivotal/microservices/accounts/AccountsConfiguration.java, src/main/java/io/pivotal/microservices/services/web/WebAccountsController.java, src/main/java/io/pivotal/microservices/services/web/WebAccountsService.java

The codebase uses java.util.logging.Logger (JUL) throughout all controller and service classes (e.g., AccountsController line 20, WebAccountsController line 27, WebAccountsService line 31, AccountsConfiguration constructor). JUL is the old Java SE logging API; SLF4J (already present on the classpath via spring-boot-starter-logging) is the modern, preferred logging facade for Spring Boot applications.

### CWE-682: Incorrect Calculation
- **Category:** Code Quality
- **Severity:** potential
- **Story Points:** 5
- **Files:** src/main/java/io/pivotal/microservices/accounts/Account.java

In Account.java, the withdraw() method (line ~94) calls balance.subtract(amount) and the deposit() method (line ~98) calls balance.add(amount), but neither assigns the return value back to balance. Since BigDecimal is immutable, these operations silently discard their results — the account balance is never actually modified by either operation, causing incorrect financial calculations.

### CWE-1057: Data Access Operations Outside of Expected Data Manager Component
- **Category:** Code Quality
- **Severity:** potential
- **Story Points:** 5
- **Files:** src/main/java/io/pivotal/microservices/accounts/AccountsConfiguration.java

In AccountsConfiguration.dataSource() (lines ~52-64), a JdbcTemplate is created and used directly to execute raw SQL queries (queryForList and update) against the database, bypassing the designated AccountRepository data manager. This violates the intended layered data access design where all database operations should go through the repository layer.

### CWE-567: Unsynchronized Access to Shared Data in a Multithreaded Context
- **Category:** Concurrency & Synchronization
- **Severity:** potential
- **Story Points:** 5
- **Files:** src/main/java/io/pivotal/microservices/accounts/Account.java

Account.java declares 'public static Long nextId = 0L' at line 24. This mutable static field is accessible to all threads without any synchronization guard. Any thread can read or overwrite nextId directly (e.g., in tests or via reflection), bypassing the synchronized getNextId() method entirely, leading to race conditions and duplicate IDs.

### CWE-662: Improper Synchronization
- **Category:** Concurrency & Synchronization
- **Severity:** potential
- **Story Points:** 8
- **Files:** src/main/java/io/pivotal/microservices/accounts/Account.java

In Account.getNextId() (lines 43-47), the synchronized block locks on the object referenced by 'nextId'. The statement 'nextId++' is equivalent to 'nextId = Long.valueOf(nextId + 1)', which replaces the reference with a new Long instance due to auto-boxing. As a result, consecutive calls acquire locks on different objects, making the synchronization ineffective — multiple threads can enter the critical section concurrently and generate duplicate IDs.

### CWE-820: Missing Synchronization
- **Category:** Concurrency & Synchronization
- **Severity:** potential
- **Story Points:** 8
- **Files:** src/main/java/io/pivotal/microservices/accounts/Account.java

The static field 'nextId' in Account.java (line 24) is declared public, allowing direct unsynchronized reads and writes from any code path outside of getNextId(). In a multithreaded Spring Boot environment handling concurrent HTTP requests, direct access to Account.nextId bypasses all synchronization, causing a data race on this shared counter.

### CWE-821: Incorrect Synchronization
- **Category:** Concurrency & Synchronization
- **Severity:** potential
- **Story Points:** 8
- **Files:** src/main/java/io/pivotal/microservices/accounts/Account.java

In Account.getNextId() (lines 43-47), 'synchronized (nextId)' locks on the Long wrapper object currently referenced by nextId. Because 'nextId++' auto-boxes to a new Long object (Integer cache applies only to small values; Long ids grow beyond the cached range), each invocation effectively synchronizes on a different object. This means the synchronization does not protect the shared state, allowing concurrent threads to read and increment nextId simultaneously, producing duplicate IDs.

### CWE-732: Incorrect Permission Assignment for Critical Resource
- **Category:** Credentials & Secrets
- **Severity:** optional
- **Story Points:** 5
- **Files:** src/main/resources/accounts-server.yml, src/main/resources/web-server.yml

Both accounts-server.yml and web-server.yml set 'management.endpoints.web.exposure.include: *', exposing all Spring Boot Actuator endpoints (including /actuator/env, /actuator/heapdump, /actuator/shutdown, /actuator/metrics, etc.) to any unauthenticated caller. No access control or authentication is configured for these endpoints, allowing unintended actors to read sensitive environment variables and potentially invoke destructive operations.

### CWE-778: Insufficient Logging
- **Category:** Credentials & Secrets
- **Severity:** potential
- **Story Points:** 3
- **Files:** src/main/java/io/pivotal/microservices/accounts/AccountsController.java

In AccountsController.byNumber() and byOwner(), when an account is not found and AccountNotFoundException is thrown (lines ~55 and ~78), no security-relevant log entry is written before the exception is raised. Similarly, failed lookups due to invalid input are not logged with adequate context (IP address, user agent, timestamp). The application has no security audit trail for unauthorized or failed access events.
