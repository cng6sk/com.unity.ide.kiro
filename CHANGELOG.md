# Changelog

All notable changes to this package will be documented in this file.

## [1.0.0] - 2026-01-21

### Added
- Initial release of Kiro Editor integration for Unity
- Support for Kiro as the default code editor in Unity
- Automatic discovery of Kiro installations on Windows, macOS, and Linux
- Generation of .csproj files for IntelliSense support
- Support for reusing existing Kiro windows
- Integration with Unity's External Tools preferences
- Support for opening files at specific line and column positions

### Changed
- Migrated from Cursor editor support to Kiro editor support
- Updated package name to com.unity.ide.kiro
- Removed Cursor and VSCodium installation support

### Technical Details
- Based on VSCode architecture (Kiro is a VSCode-based editor)
- Supports C# 11.0 language features
- Compatible with Unity 2019.4 and later
