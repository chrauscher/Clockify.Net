# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [1.1.1]
### Changed
- Change paramater name in `DeleteTimeEntryAsync` to timeEntryId
### Fixed
- DataOffset formating in `FindAllTimeEntriesForUserAsync()`

## [1.1.0]
### Added
- Support for POST /users/{userId}/activeWorkspace/{workspaceId}
### Changed
- Updated RestSharp
- Code to stopped using obselete methods.
### Removed
- Removed Q&A dependencies

## [1.0.0]
### Added
- Support for all endpoints form https://clockify.me/developers-api
	- Workspace support
	- User support
	- Client support
	- Projects support
	- Tag support
	- Task support
	- Time Entry support
	- Template support

<!-- 
===== Template =====
## [0.0.0]
### Added
### Changed
### Removed 
### Fixed
-->
