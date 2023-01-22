# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.1] - 2023-01-22

- Found that the enum used for calibration "type" was incompatible with json configuration, converted to a string; typedef uses text ring that can't be changed at runtime, so super flexible (in a negative sense), but also json compatible

## [1.0.0] - 2023-01-14

- Initial release
- Added workflow
