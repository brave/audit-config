This repository contains [a list](config.json) of audit findings to be
suppressed/ignored across [brave-core](https://github.com/brave/brave-core)
branches.

The identifier of a finding is a url, e.g.:
* `https://github.com/advisories/GHSA-36jr-mh4h-2g58`
* `https://rustsec.org/advisories/RUSTSEC-2021-0139`

The identifier is always used in the title of the GitHub issue for the finding
and in Slack notifications, e.g.:
* https://github.com/brave/brave-browser/issues/25710
  ```
  Audit finding: https://github.com/advisories/GHSA-36jr-mh4h-2g58
  ```
* https://github.com/brave/brave-browser/issues/25711
  ```
  Audit finding: https://rustsec.org/advisories/RUSTSEC-2021-0139
  ```
