# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased, will become 1.4.0]

### Changed
- Updated various PGNs in #205, #206, #200, #197, #191, #190. Affected PGNs:
  127513, 127744, 127745, 127746, 127551, 127550, 
- #192: Fixed display of PSI.
- #202: Fixed close detection of output-only streams.
- #193: Fixed compiler compatibility.
- #195: Fixed typos.

### Added
- #204: JSON output of `analyzer` will now show all not-set fields as `null` (API change).
- #194: Generate manpages with help2man if available.

## [1.3.0] - 2020-03-04

### Changed
- Fix printing of PGNs with repeating fields.
- #181: Fixed determination of whether PGN is 'fast' or 'single'.
- Updated/added various PGNs:
  126983, 126984, 126985, 126720, 130569

### Added

## [1.2.1] - 2019-02-01

### Changed
- Update PGN 127489 Fuel Pressure units (Issue 141.)
- Update PGN 127498 ASCII string lengths (Issue 142.)
- Update PGN 127498 Max Speed resolution and unit (Issue 140.)
- Update PGN 65026 Generator AC Real/Apparent Power values should be 4 bytes

## [1.2.0] - 2019-02-01

### Added
- support for Digital Yacht iKonvert
- actisense-serial supports higher baud rates 460800 and 921600 (where supported by OS)
- analyzer can read YDWG-02 logfiles
- replay utility to play back raw logfiles with same rate as they were recorded

### Changed
- Fixed calculation of negative numbers
- Minor fixes to some PGNs.

## [1.1.0] - 2018-10-27

### Added
- Add -version option to all C binaries
- Add hyperlinks to README.md.

### Changed
- Rename + rework README to README.md for better readability on GitHub.
- Reformat all C code with new .clang-format file.
- Refactor use of StringBuffer and logDebug in actisense-serial.

### Removed

## [1.0.0] - 2018-10-21
### Added
- Add version. Since this is a pretty mature product we start at 1.0.0.
- Add changelog (this file).

### Changed

### Removed

## Versions

[Unreleased]: https://github.com/canboat/canboat/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/canboat/canboat/compare/v0.1.0...v1.0.0
