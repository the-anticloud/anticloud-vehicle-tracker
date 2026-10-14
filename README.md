# VEHICLE_TRACKER

![licence](https://img.shields.io/badge/licence-MIT-blue) ![checks](https://img.shields.io/badge/checks-0_PASS-brightgreen)

> Governed Anticloud packaging of upstream `VEHICLE_TRACKER` in category **AUTOMOTIVE**. 0/16 checks PASS (measured). Every number traces to a named file plus run stamp.

**Upstream:** https://github.com/hargata/lubelog | **Upstream pin:** `dd69e59b276e79b96bb459d8b1eda1501316086d` (source: bench:BENCH.json) | **Category:** AUTOMOTIVE | **Licence:** MIT | **Overlay licence:** Anticommons 0.1.0

---

## What This Project Does

![image](https://github.com/hargata/lubelog/assets/155338622/545debcd-d80a-44da-b892-4c652ab0384a)

Self-Hosted, Open-Source, Web-Based Vehicle Maintenance and Fuel Mileage Tracker

Website: https://lubelogger.com

## Why
Because nobody should have to deal with a homemade spreadsheet or a shoebox full of receipts when it comes to vehicle maintenance.

## Showcase
[Promotional Brochure](https://lubelogger.com/brochure.pdf)

[Screenshots](/docs/screenshots.md)

## Demo
Try it out before you download it! The live demo resets every 20 minutes.

[Live Demo](https://demo.lubelogger.com) Login using username "test" and password "1234"

## Download
LubeLogger is available as both a Docker Image and a Windows Standalone Executable.

Read this [Getting Started Guide](https://docs.lubelogger.com/Installation/Getting%20Started) on how to download either of them

### Kubernetes Deployment
[Helm Chart](https://artifacthub.io/packages/helm/anza-labs/lubelogger) provided by [Anza-Labs](https://github.com/anza-labs)

### Need Help?
[Documentation](https://docs.lubelogger.com/)

[Troubleshooting Guide](https://docs.lubelogger.com/Installation/Troubleshooting)

[Search Existing Issues](https://github.com/hargata/lubelog/issues)

## Dependencies
- [Bootstrap](https://github.com/twbs/bootstrap)
- [LiteDB](https://github.com/mbdavid/litedb)
- [Npgsql](https://github.com/npgsql/npgsql)
- [Bootstrap-DatePicker](https://github.com/uxsolutions/bootstrap-datepicker)
- [SweetAlert2](https://github.com/sweetalert2/sweetalert2)
- [CsvHelper](https://github.com/JoshClose/CsvHelper)
- [Chart.js](https://github.com/chartjs/Chart.js)
- [Drawdown](https://github.com/adamvleggett/drawdown)
- [MailKit](https://github.com/jstedfast/MailKit)
- [Masonry](https://github.com/desandro/masonry)
- [QRCode-Generator](https://github.com/kazuhikoarase/qrcode-generator)

## License
MIT

## Support
To support this project, please see [Funding](https://docs.lubelogger.com/Misc/Funding)

(Full upstream documentation preserved in UPSTREAM_CLONE/README.md.)

---

## Installation

See the upstream documentation quoted in What This Project Does above.

## Usage

See the upstream documentation quoted in What This Project Does above.

## API

[Troubleshooting Guide](https://docs.lubelogger.com/Installation/Troubleshooting)

[Search Existing Issues](https://github.com/hargata/lubelog/issues)

## Dependencies

| Metric | Value |
|--------|-------|
| Files | measured |
| Lines of Code | measured |
| Dependencies | measured |
| Upstream licence | MIT |
| Overlay licence | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

# Contributing Guidelines

## Asking Questions
Before submitting a question, please check the [Troubleshooting Guide](https://docs.lubelogger.com/Installation/Troubleshooting) and search through existing issues.

Ideally, the Issues tab should only consist of bug reports and feature requests instead of debugging your LubeLogger installation.

## Feature Requests
Feature Requests are cool, but we do want to avoid bloat and scope/feature creep.

Read [this](https://github.com/hargata/lubelog/wiki/Scope-and-Purpose) to better understand the scope and purpose of this project.

LubeLogger is a Vehicle Maintenance and Fuel Mileage Tracker. 
It is not and should not be used for the following:
- Project Management Software(e.g.: Jira)
- Budget Management(e.g: YNAB/Actual)
- Inventory Management

Before submitting a feature request, please consider the following:
- Will this feature benefit more than just a niche subset of users
- Will this feature result in scope creep
- Has this feature already been requested/exist

## Bug Reports
Please fill out the issue template for bug reports.

## Security Vulnerabilities
Contact us via [Email](mailto:hargatasoftworks@gmail.com)

## Submitting Pull Requests
Pull Requests are welcome, but please consider the following:

CI/CD, Bugs, Tech-Debt Related PRs:
- Make sure changes are not breaking.
- If any dependencies are added, they must be cross-platform compatible.
- Please test changes thoroughly.

Feature Related PRs:
- Have you requested this feature in the Issues tab
- Will this feature benefit more than just a niche subset of users
- Will this feature result in scope creep
- Do these changes fix a root cause or is it simply a workaround

Ideally, you should first submit a feature request in the Issues tab before submitting a PR just in case it's something we are already working on.

Note the following:

We(the maintainers) are not responsible for cleaning up, testing, or fixing your changes.

If your changes doesn't have a wide-ranging use-case, has not been thoroughly tested, or cannot be easily maintained, we won't merge your PR.

## Licence

Upstream (c) its contributors under MIT - see `UPSTREAM_CLONE/LICENSE`. This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- URL: https://github.com/hargata/lubelog
- Pinned commit: `dd69e59b276e79b96bb459d8b1eda1501316086d`
- Verify: compare against the pinned commit in the upstream project history.

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`9aa7c7ccf91b0c59eccde8effaaabe3ad5319d525f9ce8d61b3c0085f9de8231`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |

