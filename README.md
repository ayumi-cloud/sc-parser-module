<h1 align="center">Codename: Summer CMS - Parser Module</h1>
<p align="center">(our OCMS update proposal)</p>
  
<p align="center"><img src="https://github.com/ayumi-cloud/sc-parser-module/blob/main/src/assets/images/code.svg"> <img src="https://github.com/ayumi-cloud/oc-security-module/blob/master/src/assets/images/buttons/stars.svg" alt="stars"> <img src="https://github.com/ayumi-cloud/oc-security-module/blob/master/src/assets/images/buttons/php.svg"> <img src="https://github.com/ayumi-cloud/sc-parser-module/blob/main/src/assets/images/laravel-badge.png" alt="laravel"> <img src="https://github.com/ayumi-cloud/oc-security-module/blob/master/src/assets/images/buttons/conduct.svg" alt="conduct"> <img src="https://github.com/ayumi-cloud/sc-parser-module/blob/main/src/assets/images/docs.svg" alt="docs"></p>

<p align="center"><img src="https://github.com/ayumi-cloud/sc-parser-module/blob/main/src/assets/images/cover.png"></p>

## Summer CMS Modules :eyes:

**Note: This is the parser module for Summer CMS, see here for the full list of [Summer CMS Modules](https://github.com/ayumi-cloud/sc-main/blob/main/README.md#summer-cms-modules-).**

## Table of Contents 📑

- [Transparency](#transparency-)
- [Introduction](#intro-)
- [Goals](#goals-soccer)
- [Privacy Controls](#privacy-controls-sparkles)
- [Naming Prefix](#naming-prefix-%EF%B8%8F)
- [Requirements](#requirements-)
- [Big data](#big-data-)
- [Citation](#citation-)
- [API's](#apis-gem)
- [Deprecations and removals](#deprecations-and-removals-)
- [Vendor Packages](#vendor-packages-)
- [Enhancements](#enhancements-)
- [Issues](#issues-)
- [Troubleshooting](#troubleshooting-)
    - [Something](#something-)
- [Reporting a Vulnerability](#reporting-a-vulnerability-)
- [Code of Conduct](#code-of-conduct-)
- [For Future](#for-future-)
- [Browser Support ](#browser-support-)
   - [Notes](#notes) 
- [Changelog](#changelog-)
- [Contributions, Feature Requests and Feedback](#contributions-feature-requests-and-feedback-)
	- [Testers](#testers-)
        - [With testing ](#with-testing-)
        - [Without testing](#without-testing-)
- [PSR](#psr-%EF%B8%8F)
- [PHP Coding Standards Fixer](#php-coding-standards-fixer-)
    - [Installation](#installation-)
    - [Usage](#usage-)
- [Semantic Versioning](#semantic-versioning-)
- [Copyright and License](#copyright-and-license-)

## Transparency 📢

This project is completely transparent and honest, before we started we contacted and discussed this project with the authors and admins of the October project. We have given the links to this repo to the authors and we continue to be transparent throughout the whole process! We feel it's important to state this and be open from day one! This repo contains one module, of many other modules all dedicated to different sections of the Summer CMS upgrade proposal. Instead of writing ideas and suggestions, we have taken a pro-active approach and are actively coding a fully working solution! The code is held on private repo's, due to the code being heavily developed and changed on a daily basis. We will release a stable test release to the admins and authors in private for feedback before releasing to the general public for beta-testing. This is a long-term project and we will continue to grow!

Over years we have coded and created well over a hundred pull requests (under various github accounts) which have been merged to the October core, we have never asked or recevived any money for any of the pull requests. We use the cms for professional purposes and therefore it is beneficial for our companies to have a professional working solution to give to our end-users and clients. In order for us to delivery a high quality product we made the discussion to update the cms with new and exciting features and modernize old and existing features, there are breaking change!

<p align="center"><img src="https://github.com/ayumi-cloud/sc-parser-module/blob/main/src/assets/images/data.jpg"></p>

## Introduction ⭐

The parser module can be used either in browser (client-side) or in Laravel php (server-side) environment. The parser module is used by other Summer CMS modules (such as the [Security module](https://github.com/ayumi-cloud/sc-security-module)) and in conjunction with custom Summer CMS API's to help process the data.

## Goals :soccer:

This module aims to identify the following details:

- Browser
- Layout engine
- Operating system
- Device
- Model
- Brand
- Platform
- Architecture
- Device pixel ratio (dpr)
- Device memory
- Viewport width
- Geo location
- Ip address
- Internet service provider (isp)
- Autonomous system number (asn)
- Hostname
- Host
- Referer
- Request
- Time Zone

(*) Note: The list above is not an extensive and complete list, it is intended to give a broad overview.

## Privacy Issues :sparkles:

The parser module follows strict privacy regulations set out in the GDPR, ePrivacy and California Consumer Privacy Act (CCPA). 

### Consent options ✔️

The parser module allows users to give full consent options set out by the [Legal module](https://github.com/ayumi-cloud/sc-legal-module).

### Data rentention 🗄️

There are options to configure the data retention period and the parser module follows the data retention policy.

### IP anonymization (or IP masking) 🌎

The IP anonymization/masking takes place as soon as data is received by the parser module, before any storage or processing takes place.

<p align="center"><img src="https://github.com/ayumi-cloud/sc-parser-module/blob/main/src/assets/images/ip.png"></p>

### Sensitive data 📒

The following personal data is considered **sensitive** and is subject to specific processing conditions:

- Personal data revealing racial or ethnic origin, political opinions, religious or philosophical beliefs.
- Trade-union membership.
- Genetic data, biometric data processed solely to identify a human being.
- Health-related data.
- Data concerning a person’s sex life or sexual orientation.

(*) Currently the parser module doesn't collect any personal data that is considered **sensitive** to be extra compliant to the rules.

### Encryption 🔒

Article 32 of the GDPR includes encryption as an example of an appropriate technical measure, depending on the nature and risks of your processing activities. Encryption is a widely-available measure with relatively low costs of implementation. The data processed by the parser module is encrypted before being stored.

## Naming Prefix ✒️

**Summer CMS uses the `sc-` naming prefix to advoid conflicts.**

## Requirements 🚩

This module has been optimized to work with php `7.4.x` and `8.x` versions - we recommend upgrading from any lower php version.

**A full list of requirements to install Summer CMS, can be found here: [Summer CMS Requirements](https://github.com/ayumi-cloud/sc-main/blob/main/README.md#requirements-).**

## Big data 📊

This module uses several Big Data tool sets to analyze large amounts of data collected from various Big Data sources to help detect and categorize. Some database sizes are in the petabytes and takes a few hours to run and process some models. These models are then used in our tests to improve the parsers detection rate. We also have various non-disclosed test severs running to gather various data and run tests to process the test data. This process helps us to build a more accurate parser module and helps to speed up the build process. We fully rely on using large amounts of data to build an accurate working parser used by some of the other Summer CMS modules!

## Citation 📚

<a href="https://zenodo.org/">
  <img src="https://github.com/ayumi-cloud/oc-security-module/blob/master/src/assets/images/buttons/citation.svg" />
</a>

If you use this parser module for your research, then kindly cite it. Click the above badge for more information regarding the complete citation for this parser module and the diffferent citation formats like: IEEE, APA, BibTeX, CSL, DataCite, Dublin Core, DCAT, JSON, JSON-LD, GeoJSON, MARCXML and Mendeley etc.

## API's 💎

Below are some of the API's the parser module uses (this is not a complete list):

- [Trusted Types](https://w3c.github.io/webappsec-trusted-types/dist/spec/)
- [Content Security Policy Level 3](https://www.w3.org/TR/CSP3/)
- [Content-Security-Policy-Report-Only](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy-Report-Only)
- [CSP: report-to](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy/report-to)
- [CSP: trusted-types](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy/trusted-types)
- [Fetch Metadata Request Headers](https://w3c.github.io/webappsec-fetch-metadata/)
- [User-Agent Client Hints](https://wicg.github.io/ua-client-hints/)
- [Accept-CH](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Accept-CH)
- [Accept-CH Lifetime](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Accept-CH-Lifetime)
- [Accept-Charset](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Accept-Charset)
- [Accept-Language](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Accept-Language)
- [Access-Control-Allow-Credentials](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Access-Control-Allow-Credentials)
- [Access-Control-Allow-Headers](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Access-Control-Allow-Headers)
- [Access-Control-Allow-Methods](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Access-Control-Allow-Methods)
- [Access-Control-Allow-Origin](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Access-Control-Allow-Origin)
- [Alt-Svc](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Alt-Svc)
- [Cache-Control](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Cache-Control)
- [Device-Memory](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Device-Memory)
- [DNT](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/DNT)
- [DPR](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/DPR)
- [Expect-CT](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Expect-CT)
- [Save-Data](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Save-Data)
- [User-Agent](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/User-Agent)
- [Vary](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Vary)
- [ETag](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/ETag)

## Deprecations and removals ⛔

- [Content Security Policy Level 1](https://www.w3.org/TR/CSP1/)
- [Content Security Policy Level 2](https://www.w3.org/TR/CSP2/)

The parser module has been optimized to work with CSP 3 and allow backwards compatibility with browsers supporting older CSP versions.

## Vendor Packages 🧰

- [Laravel Framework](https://github.com/laravel/framework)

**Installed version**: 6.0 or greater (Summer CMS uses latest LTS version).

## Enhancements ⭐

- The parser module has been optimized to work a long side modern browsers that support the **back/forward cache** (bfcache) api. To learn more about bfcache, see these resources:

    [Exploring a back/forward cache for Chrome](https://developers.google.com/web/updates/2019/02/back-forward-cache)

## Issues 🔨

<img alt="GitHub closed issues" src="https://img.shields.io/github/issues-closed-raw/ayumi-cloud/sc-parser-module?style=plastic"> <img alt="GitHub issues" src="https://img.shields.io/github/issues-raw/ayumi-cloud/sc-parser-module">

If you face any issue, you can create a new issue in the `Issues` tab and we will be glad to help you out!

## Troubleshooting 👿

### Something 💊

=== TO DO ===


## Reporting a Vulnerability 💥

We strive to make the code accessible to a wide audience of beginner and experienced users.

We welcome bug reports, false positive alert reports, evasions, usability issues, and suggestions for new detections. Submit these types of non-vulnerability related issues via Github.

Please include your installed version and the relevant portions of your audit log.

False negative or common bypasses should [create an issue](https://github.com/ayumi-cloud/sc-parser-module/issues/new) so they can be addressed.

Do this before submitting a vulnerability:

1) Verify that you have the latest version of Summer CMS.
2) Validate which Paranoia Level this bypass applies to. If it works in PL4, please send us an email.
3) If you detected anything that causes unexpected behavior of the engine via manipulation of existing provided rules, please send it by email.

We are happy to work with the community to provide CVE identifiers for any discovered security issues if requested.

If in doubt, feel free to reach out to us!

## Code of Conduct 💯

In order to ensure that the Summer CMS proposal community is welcoming to all, please review and abide by the [Code of Conduct](https://github.com/ayumi-cloud/sc-parser-module/blob/master/CODE_OF_CONDUCT.md).

## For Future 🔮

Shoutout to people willing to contribute to this project. Please take a look at the [projects board](https://github.com/ayumi-cloud/sc-parser-module/projects) for a list of things to be done.

## Browser Support ✅

The parser module has been tested in the following browsers:

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/ayumi-cloud/sc-parser-module/blob/main/src/assets/images/browser/chrome_48x48.png" alt="Chrome"><br>
      ✔
    </td>
    <td align="center">
      <img src="https://github.com/ayumi-cloud/sc-parser-module/blob/main/src/assets/images/browser/firefox_48x48.png" alt="Firefox"><br>
      ✔
    </td>
    <td align="center">
      <img src="https://github.com/ayumi-cloud/sc-parser-module/blob/main/src/assets/images/browser/safari_48x48.png" alt="Safari"><br>
      9+
    </td>
    <td align="center">
      <img src="https://github.com/ayumi-cloud/sc-parser-module/blob/main/src/assets/images/browser/edge_old_48x48.png" alt="Edge Legacy"><br>
      ✖ (1)
    </td>
    <td align="center">
      <img src="https://github.com/ayumi-cloud/sc-parser-module/blob/main/src/assets/images/browser/edge_48x48.png" alt="Edge"><br>
      ✔
    </td>
    <td align="center">
      <img src="https://github.com/ayumi-cloud/sc-parser-module/blob/main/src/assets/images/browser/internet-explorer_9-11_48x48.png" alt="Internet Explorer"><br>
      ✖ (2)
    </td>
    <td align="center">
      <img src="https://github.com/ayumi-cloud/sc-parser-module/blob/main/src/assets/images/browser/opera_48x48.png" alt="Opera"><br>
      ✔
    </td>
    <td align="center">
      <img src="https://github.com/ayumi-cloud/sc-parser-module/blob/main/src/assets/images/browser/samsung-internet_48x48.png" alt="Samsung"><br>
      ✔
    </td>
    <td align="center">
      <img src="https://github.com/ayumi-cloud/sc-parser-module/blob/main/src/assets/images/browser/uc_48x48.png" alt="UC"><br>
      ✔
    </td>
    <td align="center">
      <img src="https://github.com/ayumi-cloud/sc-parser-module/blob/main/src/assets/images/browser/vivaldi_48x48.png" alt="Vivaldi"><br>
      3+
    </td>
  </tr>
</table>

### Notes

(1) Microsoft announced on 17 August that Edge Legacy will have its life support switched off on 9 March 2021, Summer CMS will support Edge Chromium only.

(2) Internet Explorer version 1-11, Summer CMS will not support due to only supporting `Evergreen` brwosers.

For a full list of browser support with Summer CMS, see here: [Browser Support](https://github.com/ayumi-cloud/sc-main/blob/main/docs/browser_support.md).

## Changelog 🏆

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributions, Feature Requests and Feedback ✨

We are actively inviting new contributors! To start, please read the [contribution guide](CONTRIBUTING.md).

This project is only possible thanks to the work of many dedicated volunteers. Everyone is encouraged to help in ways large and small. Here are a few ways you can help:

- Read the current content and help us fix any spelling mistakes or grammatical errors.
- Choose an existing [issue](https://github.com/ayumi-cloud/sc-parser-module/issues) on GitHub and submit a pull request to fix it.
- Open a new issue to report an opportunity for improvement.

If you find any bugs in the code or have any improvements in mind then feel free to generate a pull request.

**Note:** Please use Unit Testing and Coding Best Practices in order to have a valid pull request 😉

Patches and pull requests are encouraged. All code should follow the [PSR-1](https://www.php-fig.org/psr/psr-1/) and [PSR-2](https://www.php-fig.org/psr/psr-2/) style guidelines. **Please include unit tests whenever possible!**

### Testers 😺

Get the `composer.json` file from the admins and install.

### With testing 🔺

```
composer update
```

### Without testing 🔻

```
composer update --no-dev
```

## PSR ♻️

This parser module uses some PSR standards to be the most interoperable possible:

- [PSR-6](https://www.php-fig.org/psr/psr-6/) Caching Interface.
- [PSR-7](https://www.php-fig.org/psr/psr-7/) Standard interfaces to represent http requests, responses and uris.
- [PSR-17](https://www.php-fig.org/psr/psr-17/) Standard factories to create PSR-7 objects.
- [PSR-18](https://www.php-fig.org/psr/psr-18/) Standard interface to send a http request and return a response.

We also suggest using Cross-browser testing provided by BrowserStack (*) where a real-browser can't be used in-house.

<p align="center"><img src="https://github.com/ayumi-cloud/oc-security-module/blob/master/src/assets/images/browser-stack.png"></p>

## PHP Coding Standards Fixer ⭕

The PHP Coding Standards Fixer (PHP CS Fixer) tool fixes your code to follow standards; whether you want to follow PHP coding standards as defined in the PSR-1, PSR-2, etc., or other community driven ones like the Symfony one.

### Installation 🔹

The recommended way to install PHP CS Fixer is to use [Composer](https://getcomposer.org/download/) in a dedicated `composer.json` file in your project, for example in the
`tools/php-cs-fixer` directory:

```console
$ mkdir --parents tools/php-cs-fixer
$ composer require --working-dir=tools/php-cs-fixer friendsofphp/php-cs-fixer
```

For more details and other installation methods, see: [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer).

### Usage 🔸

Assuming you installed PHP CS Fixer as instructed above, you can run the following command to fix the files PHP files in the `src` directory:

```console
$ tools/php-cs-fixer/vendor/bin/php-cs-fixer fix src
```

(*) Change the above command to the correct folder location.

## Semantic Versioning 🎁

The Summer CMS and all modules use: [Semantic Versioning](https://semver.org/).

<p align="center"><img src="https://github.com/ayumi-cloud/sc-security-module/blob/master/src/assets/images/semver.png"></p>

Semantic Versioning is a 3-component number in the format of `X.Y.Z` where:

- X stands for a major version.
- Y stands for a minor version.
- Z stands for a patch.

The goal of Semantic Versioning is to bring some sanity to the management of rapidly moving software release targets. As discussed above, 3 numbers i.e, `Major`, `Minor` and `Patch` are required to identify a software version. For example, if we take version `5.12.2`, then it has a `major` version of 5, a `minor` version of 12 and a `patch` version of 2.

Below are some scenarios when Summer CMS creates a new version release:

- Bump the value of X when breaking the existing API.
- Bump the value of Y when implementing new features in a backward-compatible way.
- Bump the value of Z when fixing bugs.

Pre-release metadata is identified by appending a hyphen to the end of the Semantic Versioning sequence. Thus a pre-release for version 1.0.0 could be `1.0.0-alpha.1`. Then if another build is needed, it would become `1.0.0-alpha.2` and so on. Note that names cannot contain leading zeros, but hyphens are allowed in names for pre-release identifiers.

Summer CMS uses the following pre-release metadata:

| Version     | Description        |
| ----------- | ------------------ |
| 3.3.x-aplha | The alpha phase of the release life cycle is the first phase of software testing. |
| 3.3.x-beta  | The beta phase follows after the alpha phase. A Beta phase generally begins when the software is feature complete but likely to contain a number of known or unknown bugs. |
| 3.3.x-rc    | A release candidate (RC), is a beta version with potential to becoming a stable product and is ready to release unless significant bugs emerge. |

## Copyright and License 📄

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

Everyone is permitted to copy and distribute copies of Summer CMS, but changing and hard forking are not allowed.

[⬆ back to top](#table-of-contents-)

<p align="center"><img src="https://github.com/ayumi-cloud/sc-parser-module/blob/main/src/assets/images/luv.png"></p>
