# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.1.1 - 2025-07-11

### Added

-   Missing insert key to programming layer above delete.

### Changed

-   Made delete on programming layer explicit.
-   Bumped QMK to 0.29.11

### Fixed

-   Previous EEPROM reset not removed. Replaced with intended `KC_QUES`.

## 0.1.0 - 2025-06-28

### Added

-   GASC Home Row Mods.
-   Movement layer with HJKL arrows keys, mouse controls, and jump keys.
-   Programming layer with brackets and common operators.
-   Quick access to CTRL z, x, c, and v for single-hand (left) use.
-   CAPS WORDS support with thumb key.

### Changed

-   F keys only available on alternate hand when holding a layer switch.
-   Standardize resets in top-outer corner of each board.
-   Favor tab and esc on left pinky.
-   Bumped QMK to 0.29.9.

### Removed

-   Most lighting and music controls (toggle, mode, brightness, and volume placed on movement layer)
