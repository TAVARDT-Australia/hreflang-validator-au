# Hreflang and International SEO Validator

[![Hreflang Validator](https://img.shields.io/badge/TAVARDT-Hreflang-5b3cf5.svg)](https://tools.tavardt.com/au/hreflang-checker/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Audits alternate return tags, regional language targeting, ISO 639-1 language syntax, and global x-default fallback architecture.

Developed and maintained by the international search engineering and digital standards division at **TAVARDT**.

***

## International SEO and Hreflang Audit Capabilities

* **Self-Referencing Annotation Verification**: Confirms every audited URL includes a self-referencing alternate link, avoiding search engine indexing disqualification.
* **Global x-default Fallback Inspection**: Verifies mandatory x-default routing for international visitors outside targeted geographical regions.
* **ISO 639-1 and ISO 3166-1 Syntax Validation**: Validates two-letter language and country combinations against international standards to prevent malformed regional targeting.
* **Canonical Tag Consistency**: Identifies critical conflicts where canonical link headers or tags point away from declared alternate URLs.
* **Dual-Source Parsing**: Extracts hreflang annotations from both HTML head tags and HTTP Link response headers seamlessly.
* **International Health Score**: Computes an objective 0 to 100 compliance metric classifying platforms as COMPLIANT, WARNING, or CRITICAL.

***

## Installation and Execution

Requires Python 3.8 or higher with zero external dependencies.

```bash
git clone https://github.com/TAVARDT-Australia/hreflang-validator-au.git
cd hreflang-validator-au
python hreflang_validator.py https://company.com.au
```

To output structured JSON for automated pipelines and quality audits:

```bash
python hreflang_validator.py https://company.com.au -j
```

***

## Online Diagnostic Suite

For comprehensive web testing and visual verification of international tags:

* [Hreflang Validator](https://tools.tavardt.com/au/hreflang-checker/)
* [Corporate Portal](https://ag.tavardt.com/au/)

***

## International SEO and Global Architecture Advisory

For complex multi-region architecture and alignment with W3C Internationalisation Standards, consult the technical team at **TAVARDT**.

***

## Useful Links

* **Corporate Portal:** https://ag.tavardt.com/au/
* **Diagnostic Suite:** https://tools.tavardt.com/au/
* **Technical Contact:** https://ag.tavardt.com/au/contact/

***

### License
Distributed under the MIT License. See the LICENSE file for complete terms.

***

© 2026 TAVARDT. All rights reserved.
