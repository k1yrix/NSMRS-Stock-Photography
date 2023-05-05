# Security Policy

## Supported Versions

The following table below are the **currently supported** photo sets.

| Version | Supported?          |
| ------- | ------------------ |
| 0.1.1a   | :white_check_mark: |
| 0.1a   | :white_check_mark: :exclamation: (expiration in 5 days) |

As they are still under alpha release, the typical lifespan is if they're 5 versions old from the newest release set. The set will then be deemed unsupported. Here are the other support table hierarchy:

| Release Type | Lifespan Duration | 
| ------------ | ----------------- |
| Subreleases (x.x.x) | Indefinite until next release, 2 weeks of extended support |
| Submajors (x.x) | Indefinite until next release, 1 month of extended support |
| Submajor LTS (x.xlts) | Typically 1 year after next submajor release, 2 months of extended support after mainstream expiration |
| Majors (x) | Indefinite until next release, no exceptions (for now) |
| Beta Releases (b suffix) | Indefinite until next release, follows Alpha modal, no exceptions |
| Alpha Releases (a suffix) | Indefinite until next release, 5 days to expiration, no exceptions |

*Subject to change*<br>
Major LTS will not exist lol, so don't ask

## Reporting a Vulnerability

There is no code really besides photos, but if anything poses a big of a security risk of this repo, you are to draft a security advisory in the "Security" as soon as possbile. You are to explain in detail:
- What is the vulnerability?
- How major is the vulnerability?
- Is the vulnerability zero-day?
- What items are affected in this vulnerability?

Once a security advisory is up, all branches are to be locked down to push until the vulnerability is resolved as pushing further might result the vulnerability getting worse. On occasion, pull requests might be overwritten if those pull requests are open to fix a vulnerability.
