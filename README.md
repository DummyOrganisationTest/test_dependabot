# dummy-application

[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/DummyOrganisationTest/dummy-application/badge)](https://securityscorecards.dev/viewer/?uri=github.com/DummyOrganisationTest/dummy-application)

* A demo app with with CVE, https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-34239 to simulate dependabot will update only seucurity after following recomendations from this article, https://docs.github.com/en/code-security/dependabot/dependabot-security-updates/configuring-dependabot-security-updates

* Other configurations like scorecard action

As result, dependabot configuration follow the snippet below

```python
version: 2
updates:
  - package-ecosystem: pip
    directory: /
    schedule:
      interval: daily
    open-pull-requests-limit: 0
```
