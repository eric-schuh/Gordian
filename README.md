# 🛠 The Gordian System

### **Architect:** _[Christopher Allen](https://github.com/ChristopherA)_<br/>
**Developer:** _[Wolf McNally](https:github.com/WolfMcNally)_
* <img src="https://github.com/BlockchainCommons/Gordian/blob/master/Images/logos/gordian-icon.png" width=16 valign="bottom"> ***uses [gordian](https://github.com/BlockchainCommons/gordian/blob/master/README.md) technology***
* <img src="https://raw.githubusercontent.com/BlockchainCommons/torgap/master/images/logos/torgap.png" width=30 valign="bottom"> ***uses [torgap](https://github.com/BlockchainCommons/torgap/blob/master/README.md) technology***

![](Images/logos/gordian-overview-screen.png)

The Gordian system is all about user agency & security. It's intended to support the self-sovereign control of digital assets in a way that's safe, secure, and private by enabling responsible key management, [cutting through a traditionally knotty problem in Bitcoin development.](Docs/Why-Gordian.md). The Gordian system is built on a foundation of Principles that have been fulfilled in an Architecture that is embodied in Reference Apps and supported by Reference Libraries.

* **Gordian Principles.** A mission statement of four core principles that support self-sovereign control of digital assets.
* **Gordian Architecture.** The design for both the overall architecture and the individual specifications that make it possible.
* **Gordian Reference Apps.** A set of applications that demonstrate the Gordian Architecture, its Principles, its specifications, and its Libraries.
* **Gordian Reference Libraries.** A set of libraries that allow developers to incorporate Gordian specifications and expand the Gordian ecosystem.
* **#SmartCustody.** Educational programs meant to support the Gordian Principles.

The ultimate goal of the Gordian System is to create a community of developers who have followed the examples of the Gordian Reference Apps and used the Gordian Reference Libraries to build their own applications that embody the GOrdian Architecture and fulfill the Gordian Principles.

*This repo contains a table of contents for various the Gordian system projects and features. Please see individual repos and pages for more information.*

## Gordian Principles

Blockchain Commons' interoperable specifications are meant to support four core principles that put the user first and that enable responsible key management:

* **Independence.** Gordian improves user freedom from involuntary oversight or external control.
* **Privacy.** Gordian protects against coercion with non-correlation, privacy, and pseudonymity.
* **Resilience.** Gordian protects users to decrease the likelihood of them losing their funds via any means.
* **Openness.** Gordian supports open infrastructure that allows developers to create their own applications.

Look at individual Blockchain Commons reference apps for guidance on how each acts as a model for these principles and [#SmartCustody Case Studies](https://github.com/BlockchainCommons/SmartCustody/blob/master/Docs/Case-Studies-Overview.md) for how professional hardware & software apps do so.

## Gordian Architecture

The Gordian Architecture puts the Gordian Principles into use through an overall design that covers everything that from the high-level architecture of a Gordian ecosystem through the specification and UX best practices that make it possible.

* **Gordian Macro-Architecture.** The ecosystem architecture depends on functional partition, separating services and confidential data.
* **Data Format.** CBOR is used as the canonical data structure for the Gordian Architecture.
* **Encoding Specifications.** Bytewords, URs, and (optionally) QR Codes ensure that Gordian services are interoperable.
* **Backup Specifications.** UR specifications make it easy to backup confidential data, creating Resilience.
* **Communication Specifications.** Further UR specifications such as envelopes and request/responses aid interoperable communication.
* **Secure UX Designs.** UX best practices form another layer of support for the Gordian Principles.

Please see [The Gordian Architecture](Overview-Architecture.md) for more in-depth discussion of all the architectural elements and [Gordian Architecture Roles](Overview-Roles.md) for examples of functions that can be partitioned within the Macro-architecture.

Together, these elements (in particular: a network coordinator such as Gordian Coordinator; a signing device such as Gordian Seed Tool; encoding specifications such URs; and communication specifications such as envelope, request, and response) comprise what we consider a Minimal Viable Architecture (MVA) for Gordian, and thus for safe, self-sovereign architecture. They're the minimum that's needed to properly support users.

### Video Overview

This video overview covers many of the technologies found in the Gordian Architecture:
<center>
  <a href="https://www.youtube.com/watch?v=RYgOFSdUqWY"><img src="/Images/video-tech-overview.png"></a>
</center>

## Gordian Reference Apps

Gordian Reference Apps demonstrate the elements of how the Gordian Architecture and how they can be used to fulfill the Gordian Principles. Our Gordian Reference Apps undergoing the most development currently include:

* **Gordian Coordinator.** A Networked transaction coordinator.
* **Gordian Seed Tool.** An Airgapped seed vault & signing device.
* **SpotBit.** A Micro-pricing service.

Please see [The Gordian Reference Apps](https://github.com/BlockchainCommons/Gordian/blob/shannona-gordian-revision/Docs/Overview-Apps.md) for a complete list of past and present reference apps, links to their repos, and an example of how they can be combined into a Macro-Architecture. Links to CLI apps are also included.

## Gordian Reference Libraries

The Gordian Reference Libraries allow you to easily use many of the specifications that lay the foundation for the Gordian Architecture. Our foundational libraries are usually written in C or C++, but many have many converted in other languages such as Java, Python, and Swift.

The core libraries are:

* **bc-bytewords.** A library for encoding binary data into Bytewords.
* **bc-lifehash.** A library for creating Lifehash visual hashes.
* **bc-sskr.** A library for sharding a secret and converting it to Bytewords or URs.
* **bc-ur.** A library for encoding binrary data as URs.

Please see [The Gordian Reference Libraries](https://github.com/BlockchainCommons/crypto-commons#gordian-reference-libraries) for a complete list of libraries in a variety of languages.

## #SmartCustody Articles

Please see the [SmartCustody repo](https://github.com/BlockchainCommons/SmartCustody) for articles on Multisigs, Timelocks, and other SmartCustody topics.

## Discussions

The best place to talk about Blockchain Commons and its projects is in our GitHub Discussions areas.

[**Gordian System Discussions**](https://github.com/BlockchainCommons/Gordian/discussions). For users and developers of the Gordian system, including the Gordian Server, Bitcoin Standup technology, QuickConnect, and the Gordian Wallet. If you want to talk about our linked full-node and wallet technology, suggest new additions to our Bitcoin Standup standards, or discuss the implementation our standalone wallet, the Discussions area of the [main Gordian repo](https://github.com/BlockchainCommons/Gordian) is the place.

[**Blockchain Commons Discussions**](https://github.com/BlockchainCommons/Community/discussions). For developers, interns, and patrons of Blockchain Commons, please use the discussions area of the [Community repo](https://github.com/BlockchainCommons/Community) to talk about general Blockchain Commons issues, the intern program, or topics other than the [Gordian System](https://github.com/BlockchainCommons/Gordian/discussions) or the [wallet standards](https://github.com/BlockchainCommons/AirgappedSigning/discussions), each of which have their own discussion areas.

## Status - Varied

Please see individual projects for current status.

## Origin, Authors, Copyright & Licenses

Unless otherwise noted (either in this [/README.md](./README.md) or in the file's header comments) the contents of this repository are Copyright © 2020 by Blockchain Commons, LLC, and are [licensed](./LICENSE) under the [spdx:BSD-2-Clause Plus Patent License](https://spdx.org/licenses/BSD-2-Clause-Patent.html).

In most cases, the authors, copyright, and license for each file reside in header comments in the source code. When it does not, we have attempted to attribute it accurately in the table below.

This table below also establishes provenance (repository of origin, permalink, and commit id) for files included from repositories that are outside of this repo. Contributors to these files are listed in the commit history for each repository, first with changes found in the commit history of this repo, then in changes in the commit history of their repo of their origin.

| File      | From                                                         | Commit                                                       | Authors & Copyright (c)                                | License                                                     |
| --------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------ | ----------------------------------------------------------- |


## Financial Support

The Gordian system is a project of [Blockchain Commons](https://www.blockchaincommons.com/). We are proudly a "not-for-profit" social benefit corporation committed to open source & open development. Our work is funded entirely by donations and collaborative partnerships with people like you. Every contribution will be spent on building open tools, technologies, and techniques that sustain and advance blockchain and internet security infrastructure and promote an open web.

To financially support further development of the Gordian system and other projects, please consider becoming a Patron of Blockchain Commons through ongoing monthly patronage as a [GitHub Sponsor](https://github.com/sponsors/BlockchainCommons). You can also support Blockchain Commons with bitcoins at our [BTCPay Server](https://btcpay.blockchaincommons.com/).

## Contributing

We encourage public contributions through issues and pull requests! Please review [CONTRIBUTING.md](./CONTRIBUTING.md) for details on our development process. All contributions to this repository require a GPG signed [Contributor License Agreement](./CLA.md).

### Discussions

The best place to talk about Blockchain Commons and its projects is in our GitHub Discussions areas.

[**Gordian System Discussions**](https://github.com/BlockchainCommons/Gordian/discussions). For users and developers of the Gordian system, including the Gordian Server, Bitcoin Standup technology, QuickConnect, and the Gordian Wallet. If you want to talk about our linked full-node and wallet technology, suggest new additions to our Bitcoin Standup standards, or discuss the implementation our standalone wallet, the Discussions area of the [main Gordian repo](https://github.com/BlockchainCommons/Gordian) is the place.

[**Wallet Standard Discussions**](https://github.com/BlockchainCommons/AirgappedSigning/discussions). For standards and open-source developers who want to talk about wallet standards, please use the Discussions area of the [Airgapped Signing repo](https://github.com/BlockchainCommons/AirgappedSigning). This is where you can talk about projects like our [LetheKit](https://github.com/BlockchainCommons/bc-lethekit) and command line tools such as [seedtool](https://github.com/BlockchainCommons/bc-seedtool-cli), both of which are intended to testbed wallet technologies, plus the libraries that we've built to support your own deployment of wallet technology such as [bc-bip39](https://github.com/BlockchainCommons/bc-bip39), [bc-slip39](https://github.com/BlockchainCommons/bc-slip39), [bc-shamir](https://github.com/BlockchainCommons/bc-shamir), [Shamir Secret Key Recovery](https://github.com/BlockchainCommons/bc-sskr), [bc-ur](https://github.com/BlockchainCommons/bc-ur), and the [bc-crypto-base](https://github.com/BlockchainCommons/bc-crypto-base). If it's a wallet-focused technology or a more general discussion of wallet standards,discuss it here.

[**Blockchain Commons Discussions**](https://github.com/BlockchainCommons/Community/discussions). For developers, interns, and patrons of Blockchain Commons, please use the discussions area of the [Community repo](https://github.com/BlockchainCommons/Community) to talk about general Blockchain Commons issues, the intern program, or topics other than the [Gordian System](https://github.com/BlockchainCommons/Gordian/discussions) or the [wallet standards](https://github.com/BlockchainCommons/AirgappedSigning/discussions), each of which have their own discussion areas.

### Other Questions & Problems

As an open-source, open-development community, Blockchain Commons does not have the resources to provide direct support of our projects. Please consider the discussions area as a locale where you might get answers to questions. Alternatively, please use this repository's [issues](./issues) feature. Unfortunately, we can not make any promises on response time.

If your company requires support to use our projects, please feel free to contact us directly about options. We may be able to offer you a contract for support from one of our contributors, or we might be able to point you to another entity who can offer the contractual support that you need.

### Credits

The following people directly contributed to this repository. You can add your name here by getting involved. The first step is learning how to contribute from our [CONTRIBUTING.md](./CONTRIBUTING.md) documentation.

| Name              | Role                | Github                                            | Email                                 | GPG Fingerprint                                    |
| ----------------- | ------------------- | ------------------------------------------------- | ------------------------------------- | -------------------------------------------------- |
| Christopher Allen | Principal Architect | [@ChristopherA](https://github.com/ChristopherA) | \<ChristopherA@LifeWithAlacrity.com\> | FDFE 14A5 4ECB 30FC 5D22  74EF F8D3 6C91 3574 05ED |

## Responsible Disclosure

We want to keep all of our software safe for everyone. If you have discovered a security vulnerability, we appreciate your help in disclosing it to us in a responsible manner. We are unfortunately not able to offer bug bounties at this time.

We do ask that you offer us good faith and use best efforts not to leak information or harm any user, their data, or our developer community. Please give us a reasonable amount of time to fix the issue before you publish it. Do not defraud our users or us in the process of discovery. We promise not to bring legal action against researchers who point out a problem provided they do their best to follow the these guidelines.

### Reporting a Vulnerability

Please report suspected security vulnerabilities in private via email to ChristopherA@BlockchainCommons.com (do not use this email for support). Please do NOT create publicly viewable issues for suspected security vulnerabilities.

The following keys may be used to communicate sensitive information to developers:

| Name              | Fingerprint                                        |
| ----------------- | -------------------------------------------------- |
| Christopher Allen | FDFE 14A5 4ECB 30FC 5D22  74EF F8D3 6C91 3574 05ED |

You can import a key by running the following command with that individual’s fingerprint: `gpg --recv-keys "<fingerprint>"` Ensure that you put quotes around fingerprints that contain spaces.
