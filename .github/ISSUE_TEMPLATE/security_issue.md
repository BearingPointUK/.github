---
name: Security Issue template
about: All security related changes must use this issue type.
title: Describe what the security problem is
labels: security
assignees: ''

---
*Please complete each section and remove the instructions.*
*Security issues will **always** be fixed, regardless of the risk or work involved.*

# What is the security isssue?

Please describe the security issue? Reference an [OWASP vulnerability](https://owasp.org/www-community/vulnerabilities/) or a [CVE](https://www.cve.org/) or [CWE](https://cwe.mitre.org/) if at all possible.

# What is proposed fix?

Please describe the proposed fix.

# What are the acceptance criteria?

Please describe how we know that the security fix has been made and is effective. 

In the case of our code, wherever possible this should describe a test that currently fails due to the security issue.
When the issue is fixed teh test should then pass.

In the case of an upgrade of a 3rd party dependency this should reference the old and new versions and if possible highlight the security change make in the 3rd party library, e.g. via the release notes or a link to a github issue.
