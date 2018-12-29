# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
 - This changelog.
 - Support for `.col-md-12` to `.row-border-group`
   - This allows borders to be added to `[container:col-md-12]` blocks that span an entire row.
 - Support for `.panel-npcsheet`
 - Support for WorldAnvil Maps v2.0
    - Information sidebar (Using the `.user-css-map-sidebar` selector)

### Changed
 - Colors used for horizontal rules (`[hr]`)
   - `hr` now uses `default` color
   - `hr` contained in `.panel-primary` and `.panel-npcsheet` now uses `primary` color

### Fixed
 - Missing background for embedded image thumbnails (Transparent default color)
 - Incorrect color used for embedded image artist credits (Now using primary color)
