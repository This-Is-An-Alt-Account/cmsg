# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Web: Toggle for light/dark theme.
- HTML override for main that adds styling and scripts to add a warning when viewing a page in the cmsg/dev path.

### Changed
- Edited mkdocs config to recognize overrides.
- Modified actions workflow to have new job for pushes on dev and to generate a separate mkdocs based off the dev branch into dev/ on the gh-books branch.
