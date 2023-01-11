# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
Types of changes: Added, Changed, Deprecated, Removed, Fixed, Security.

## [2.6.1] - 2023-01-11
### Fixed
- Fix native discovery 

## [2.5.3] - 2022-08-04
### Fixes
- Fix issue on package creation. Now it's possible to integrate the SDK on 3rd parties' library.

## [2.5.2] - 2020-01-26
### Fixed
- Minor security improvements to Android service.

## [2.5.1] - 2020-12-11
### Fixed
- Major fix to discovery engine to prevent mixing different sources for ARP table across rounds.

## [2.5.0] - 2020-10-28
### Fixed
- Increased minimum SDK version to 22 (LOLLIPOP_MR1) to remove custom trust manager.
- Minor fixes to discovery engine to address sporadic crashes.

## [2.4.2] - 2020-09-09
### Fixed
- Fixed an issue that was preventing device recognition to complete in some case.

## [2.4.1] - 2020-08-26
### Changed
- Uses okHttp backward-compatible method so that okHttp 3.x can also be used instead of the
official okHttp 4.x.

## [2.4.0] - 2020-07-24
### Changed
- Removed dependencies from deprecated Apache Http and replaced with okHttp.

### Fixed
- Bugs in the scanning engine.

## [2.3.0] - 2019-11-11
### Added
- MAC addresses in the scan are back. The new engine provides again the MAC address on Android SDK.

## [2.2.0] - 2019-08-27
### Added
- Support for Android 10.
- Discards Fake MAC addresses in the output.
- Adds new property isLLA and isFake to clarify which detected devices have fake or randomised.
MAC Addresses

### Fixed
- Bugs in the scanning engine.
- Incorrect inclusion of SNMP library.
