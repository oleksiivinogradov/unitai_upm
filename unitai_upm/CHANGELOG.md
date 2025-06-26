# Changelog

All notable changes to this project will be documented in this file.

## [1.1.1] - 2025-01-27

### Fixed
- **Unity Package Meta Files**: Fixed missing .meta file for CHANGELOG.md in Unity packages

## [1.1.0] - 2025-06-26

### Added
- **Agent Mode**: Fully functional AI agent mode with autonomous operations including script creation, modification, file management, and GameObject operations
- **Command Pool System**: New sequential command execution system with user approval workflow for all file and GameObject operations
- **GameObject and Component Removal**: Full support for removing entire GameObjects and specific components with safety warnings
- **Screenshot Functionality**: New ability to capture and include screenshots in conversations
- **File Creation and Management**: Enhanced file creation system with approval workflows and better error handling
- **Advanced Search Capabilities**: Improved file search and codebase search functionality
- **Asset Postprocessor Enhancements**: Enhanced automatic project indexing and embedding generation
- **Chat History Cleanup Utility**: New utility for managing and cleaning chat history data

### Changed
- **Major UI Improvements**: Enhanced user interface with better color schemes, layout improvements, and visual feedback
- **Performance Optimizations**: Significant performance improvements in UI rendering, syntax highlighting, and file operations
- **Model Interface Enhancements**: Improved API communication with better error handling and response processing
- **Project Indexing**: Enhanced project embedding service with better file processing and indexing
- **Command Execution Flow**: Redesigned command execution to be more reliable with domain reload survival
- **Save Mode Persistence**: Improved persistence of user preferences and settings

### Fixed
- **Chat History Management**: Fixed issues with conversation loading, saving, and message processing
- **Command Execution**: Resolved various command execution bugs and improved reliability
- **UI Responsiveness**: Fixed UI lag and rendering issues during heavy operations
- **File Operations**: Improved file creation and modification handling with better error recovery
- **Memory Management**: Enhanced memory usage and reduced memory leaks in long-running operations
- **Domain Reload Handling**: Improved handling of Unity compilation and domain reload cycles

### Technical Details
- Enhanced system prompt capabilities with removal operations
- Improved Unity compatibility across different Unity versions
- Better error reporting and debugging capabilities
- Enhanced code syntax highlighting performance

## [1.0.4] - 2025-06-18

### Added
- Image generation and editing capabilities.
- UI elements for image aspect ratio, selection, and cropping.

### Changed
- Sanitized JSON in commands for better reliability.
- Improved image dimension handling.

### Fixed
- Addressed various issues related to image generation and display, including borders and backgrounds.

## [1.0.3] - 2024-07-26

### Added
- Code search functionality.
- Code snippets in chat.

### Changed
- Major UI improvements for a better user experience.
- Improved font loading and rendering.

### Fixed
- Fixed an issue with command execution.
- Implemented a character limit to prevent errors.
- Miscellaneous bug fixes and stability improvements.

## [1.0.0] - YYYY-MM-DD
 
### Added
- Initial release. 