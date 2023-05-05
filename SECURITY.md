# Security Policy

## Supported Versions

The following table below are the **currently supported** photo sets.

| Version | Supported?          |
| ------- | ------------------ |
| 0.1.1a   | :white_check_mark: |
| 0.1a   | :white_check_mark: |

As they are still under alpha release, the typical lifespan is if they're 5 versions old from the newest release set. The set will then be deemed unsupported. Here are the other support table hierarchy:

| Release Type | Lifespan Duration | 
| ------------ | ----------------- |
| Subreleases | 2 weeks after subrelease, otherwise indefinite |
| Submajors | 1 month |
**wip not complete yet**

## Reporting a Vulnerability

There is no code really besides photos, but if anything poses a big of a security risk of this repo, you are to draft a security advisory in the "Security" as soon as possbile. You are to explain in detail:
- What is the vulnerability?
- How major is the vulnerability?
- Is the vulnerability zero-day?
- What items are affected in this vulnerability?

Once a security advisory is up, all branches are to be locked down to push until the vulnerability is resolved as pushing further might result the vulnerability getting worse. On occasion, pull requests might be overwritten if those pull requests are open to fix a vulnerability.
