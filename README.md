# Image SEO and Visual Accessibility Auditor

[![Image SEO Auditor](https://img.shields.io/badge/TAVARDT-Image%20SEO-5b3cf5.svg)](https://tools.tavardt.com/uk/image-seo-checker/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Audits alt text completeness, modern format adoption (WebP/AVIF), layout stability dimensions, and descriptive filenames.

Developed and maintained by the search architecture and visual accessibility division of **TAVARDT**.

***

## Image SEO and Accessibility Audit Capabilities

* **Alt Attribute Completeness and Quality**: Audits alternative text coverage across all image elements, highlighting missing, generic, or empty descriptions.
* **Next-Gen Format Adoption**: Evaluates deployment of modern WebP and AVIF formats against legacy JPEG and PNG files.
* **Layout Shift Prevention (CLS)**: Confirms explicit `width` and `height` dimensional declarations.
* **Lazy Loading Implementation**: Audits `loading="lazy"` attributes on non-critical images to speed up First Contentful Paint.
* **Image Optimisation Health Score**: Quantitative 0 to 100 health score with prioritized technical remediation steps.

***

## Installation and Execution

Requires Python 3.8 or higher with no external dependencies required.

```bash
git clone https://github.com/TAVARDT-UK/image-seo-validator-uk.git
cd image-seo-validator-uk
python image_seo_validator.py https://company.co.uk
```

To output results in structured JSON format:

```bash
python image_seo_validator.py https://company.co.uk -json
```

***

## Comprehensive Web Diagnostic

For full web verification and deep image catalog audits:

* **Official Image SEO Checker Tool**
* **TAVARDT Enterprise Portal**

***

## Visual Accessibility and Media Optimisation Advisory

For enterprise digital catalogues aligning with W3C WCAG Standards and UK Search Architecture Guidelines, contact the specialists at **TAVARDT**.

***

## Useful Links

* **Corporate Portal:** https://ag.tavardt.com/uk/
* **Diagnostic Suite:** https://tools.tavardt.com/uk/
* **Technical Contact:** https://ag.tavardt.com/uk/contact/

***

### License
Released under the MIT License. See [LICENSE](LICENSE) for full details.

***

© 2026 TAVARDT. All rights reserved.
