# Kin Foundation - Open Source Manifest

> Status: (0.0.0 Draft)

## Abstract

The Kin Foundation is committed to working together with developers from the Kin Community to develop all Open Source Software in the open.

## Managed Projects

This document applies to the following Open Source Software (OSS) projects maintained by the Kin Foundation:

### Services

- [kinecosystem/agora](https://github.com/kinecosystem/agora)
- [kinecosystem/agora-api](https://github.com/kinecosystem/agora-api)

### SDKs

- [kinecosystem/kin-android](https://github.com/kinecosystem/kin-android)
- [kinecosystem/kin-go](https://github.com/kinecosystem/kin-go)
- [kinecosystem/kin-ios](https://github.com/kinecosystem/kin-ios)
- [kinecosystem/kin-node](https://github.com/kinecosystem/kin-node)
- [kinecosystem/kin-python](https://github.com/kinecosystem/kin-python)

## Release Strategy SDKs

A lot of successful open source projects have a release strategy that allows them to ship updates to their software frequently in a predictable way.

There are a lot of benefits to an approach like this:

- Consumers of the SDKs know when a new version will be released, and can plan around this.
- The dependencies of the SDKs get updated frequently.
- The project always has activity on GitHub.
- The releases become part of the routine for the team.

### Minor releases (bi-weekly)

Every other week on Thursday, the Kin Foundation will release a new version of all their SDKs.

These versions include updates of any dependencies, bug-fixes and non-breaking changes.

The developers consuming these updates are advised to use them, but can choose to skip a few minor versions.

### Major releases (bi-yearly)

Twice a year, in October and April (TBD), the Kin Foundation will release a ‘major’ release of each of the managed projects.

A Major release can contain breaking changes, add deprecations, remove functionality and add functionality that previously did not exist.

## Release Strategy

### Minor Versions

We need to get started releasing minor versions as soon as possible.

It’s not realistic to conform to this schedule with all the 5 SDKs at once. A better idea is probably to start doing this and add a new SDK each time.

Using a schedule like this, we should be up to full speed within 2 months.

> ⚠️ This is a tentative schedule. Exact versions and dates are to be determined.

| Date       | Node  | Go    | Python | Android | iOS   |
| ---------- | ----- | ----- | ------ | ------- | ----- |
| Jul 15, 21 | 1.0.0 | ---   | ---    | ---     | ---   |
| Jul 29, 21 | 1.1.0 | 1.1.0 | ---    | ---     | ---   |
| Aug 12, 21 | 1.2.0 | 1.2.0 | 1.2.0  | ---     | ---   |
| Aug 26, 21 | 1.3.0 | 1.3.0 | 1.3.0  | 2.0.0   | ---   |
| Sep 09, 21 | 1.4.0 | 1.4.0 | 1.4.0  | 2.1.0   | 2.1.0 |
| Sep 23, 21 | 1.5.0 | 1.5.0 | 1.5.0  | 2.2.0   | 2.2.0 |
| Oct 07, 21 | 1.6.0 | 1.6.0 | 1.6.0  | 2.3.0   | 2.3.0 |
| Oct 21, 21 | 1.7.0 | 1.7.0 | 1.7.0  | 2.4.0   | 2.4.0 |

### Major Versions

A major version can be either a ‘stable’ release with Long Term Support (LTS) or an unstable release (Non-LTS).

The LTS will be supported for a year, until the new LTS comes out. Consumers of the SDKs are recommended to use an LTS release and upgrade at least once a year.

The Non-LTS version will be supported for half a year, and be deprecated with the release of the new LTS.

Consumers of the SDKs that want to use the bleeding edge of the Kin SDKs are encouraged to test these releases at their own risk.

| Date   | LTS | End of Life         |
| ------ | --- | ------------------- |
| Oct 21 | LTS | Supported to Oct 22 |
| Apr 22 | -   | Supported to Oct 22 |
| Oct 22 | LTS | Supported to Oct 23 |
| Apr 23 | -   | Supported to Oct 23 |
| Oct 23 | LTS | Supported to Oct 24 |
| Apr 24 | -   | Supported to Oct 24 |

## Release Strategy Agora

The release schedule for Agora is something that will be decided after having implemented the release schedule for the SDKs, but will most likely be organized in a very similar way.

## RFC Process

The Kin Foundation is working on formalizing an RCF (Request For Comment) Process that will be used to gauge feedback from the Kin Developers Community for large and impactful changes.
