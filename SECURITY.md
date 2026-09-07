# Security Policy

## Scope and Supported Versions

This is the default security policy for repositories in the PicPeak organization.
A repository's own `SECURITY.md` takes precedence and defines any project-specific
supported versions and release channels.

For the PicPeak application, see its
[security policy](https://github.com/PicPeak/picpeak/blob/main/SECURITY.md)
for support and security releases on `stable` and `main`.

Other projects have independent versioning. Follow the supported releases stated
in the affected repository. For projects without versioned releases, use the
current default branch and deploy its latest fixes. PicPeak application version
numbers do not define support for the usage collector, documentation or other
repositories.

Security fixes are delivered through all supported release channels of the
affected project. Superseded releases are not maintained separately unless the
repository explicitly documents otherwise.

## Reporting a Vulnerability

**Do not report vulnerabilities in public issues, discussions or pull requests.**

- Use **Report a vulnerability** under the affected repository's **Security** tab
  when private vulnerability reporting is available.
- If the repository does not offer private reporting, or you cannot use GitHub,
  email **info@picpeak.app**.
- For the PicPeak application, the
  [private reporting form](https://github.com/PicPeak/picpeak/security/advisories/new)
  is available directly.

Include the repository and component, affected version or commit, deployment
method, reproduction steps, expected impact and any suggested fix. Remove
credentials and personal data from logs and examples.

## Response and Disclosure

We aim to acknowledge reports within 48 hours. This is a response target, not a
guaranteed service level or a promised resolution time. We will provide progress
updates and coordinate disclosure with the reporter.

Security advisories and release notes identify affected versions or commits,
available fixes and any required mitigation or upgrade steps. Reporter credit is
optional and included with permission.

## Deployment and General Support

Use the affected project's deployment documentation for security configuration,
updates and backups. Follow its support guide for ordinary bugs and questions.
