# Security Policy

Version|Support status
-----:|:----:
`4.x`    |:white_check_mark:
`<= 3.x` |:x:

_Legend_:
  - ✅ Currently supported, receives all security and other updates
  - 🔙 Legacy support, receives backported security updates only
  - ❌ Unsupported


## Private Disclosure Process

The Vapor Core Team ask that known and suspected vulnerabilities be privately and responsibly disclosed by [filling out a vulnerability report](https://github.com/vapor/vapor/security/advisories/new) on Github[^1]. Vulnerabilities may also be privately and responsibly disclosed by emailing all pertinent information to [security@vapor.codes](mailto:security@vapor.codes).

[^1]: See [Github's official documentation of the vulnerability report feature](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability) for additional privacy and safety details.

**⚠️ Please do _not_ file a public issue! ⚠️**

### When to report a vulnerability

* You think you have discovered a potential security vulnerability in a Vapor package.
* You are unsure how a vulnerability affects a Vapor package.

### What happens next?

* A member of the team will acknowledge receipt of the report within 3 working days. This may include a request for additional information about reproducing the vulnerability.
* We will privately inform the Swift Server Work Group ([SSWG](https://github.com/swift-server/sswg)) of the vulnerability within 10 days of the report as per their [security guidelines](https://github.com/swift-server/sswg/blob/main/security/README.md).
* Once we have identified a fix we may ask you to validate it. We aim to do this within 30 days. In some cases this may not be possible, for example when the vulnerability exists at the protocol level and the industry must coordinate on the disclosure process.
* If a CVE number is required, one will be requested through the [GitHub security advisory process](https://docs.github.com/en/code-security/security-advisories), providing you with full credit for the discovery.
* We will decide on a planned release date and let you know when it is.
* Prior to release, we will inform major dependents that a security-related patch is impending.
* Once the fix has been released we will publish a security advisory on GitHub and in the Server → Security Updates category on the [Swift forums](https://forums.swift.org/c/server/security-updates/).
