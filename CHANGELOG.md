# Changelog

## [1.1.0] - 2025-10-29

### Added

- **Release Automation System**: Automated release process with version bumping, build, packaging, and deployment to releases repository
  - New release scripts supporting patch, minor, and major version increments
  - Automatic ZIP file generation with versioned filenames
  - Automatic updates to releases repository README and CHANGELOG
- **Slack Integration**: Automated Slack notifications for new releases
  - Formatted release announcements with download links
  - Automatic notification after successful releases
  - Manual notification support for retry scenarios
- **New NPM Scripts**: Streamlined release workflow
  - `release:patch/minor/major` - Automated versioned releases
  - `release:to-releases` - Quick builds without version bump
  - `notify:slack` - Manual Slack notification trigger
- **GitHub Integration Script**: Slack-to-GitHub webhook script for creating issues
  - `scripts/slack-github-webhook.js` - Webhook server for creating GitHub issues from Slack

### Changed

- Enhanced ESLint configuration for build scripts with proper Node.js environment support

### Fixed

- Release automation now properly handles private repository workflows



All notable changes to Form Flow Maestro will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.9] - 2024-XX-XX

### Initial Release

- Initial release of Form Flow Maestro Chrome Extension
