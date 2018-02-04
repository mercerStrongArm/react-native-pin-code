# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [v0.3.0] - 2018-02-04

### Added

* New prop `checkPinCode`. Called to check pin code (`code` prop is not used if `checkPinCode` prop is present)

### Changed

* Update Readme to add simple example.

### Fixed

* Use `code.length` if `number` prop is not used.