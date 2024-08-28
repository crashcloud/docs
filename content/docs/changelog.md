---
title: Changelog
type: docs
sidebar:
  open: true
prev: known-issues
toc: true
weight: 100
---

## 1.5.0-wip [Unreleased]

### Added

- New Supported Elements
  - Layers
  - User Strings
- LOTS of new docs! http://crsh.cloud/
- Auth - Crash now authenticates with your Rhino Account

### Fixed

- Crash sends changes MUCH faster (init is still a bit slow)
- Improved Joining a Model Experience
- Crash redraws more to make recieving changes more responsive
- Improved Collaborators Panel to show current user and improved placement
- Further UI/UX Improvements
- Crash handles server joining exceptions MUCH better
- Loading model Progress bar should be much more useful and responsive
- Sending changes is now async and non blocking
- Fixed some unicode/utf-8 string issues that caused weird bugs

### Changed

- Crash can now send key/value pairs in changes

## 1.4.0-wip

### Added

- Relase Selected → Users can now release individual changes
- Undo/Redo Support
- Complex Operation support, e.g. Boolean Union
- Better Join Shared Model UI
- Better User UI
- Headless scripting support
- Fully Mac Compatible (including net 7.0)
- Full Rhino 8 Support
- Native DarkMode support for Rhino 8

### Fixed

- Full Undo/Redo Support, many fewer bugs
- Complex Operation support, e.g. Boolean Union
- Handled connection failures much more gracefully
- Fixed a lot of ironic Crashes

### Changed

- Removed StartSharedModel as it was a bad solution
- Crash is almost entirely async
- Crash uses an entirely immutable database now. Modifications are now change based and more efficient

# 1.3.1

- 3rd party plugin support: Crash has a new API that will allow 3rd party plugins to go multi-user!
- New User UI: Added a small UI to show users and allow for toggling
- User cameras: You can now see and follow other users’ cameras
- Numerous bug fixes: We’ve addressed several issues reported by our users, ensuring a smoother and more reliable experience.
- Improved responsivity: Enjoy a faster and more responsive user experience

## 1.0.0 (Alpha)

- Initial Crash Release!
