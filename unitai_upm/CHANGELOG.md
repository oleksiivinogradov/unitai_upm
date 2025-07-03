# Changelog

All notable changes to this project will be documented in this file.

## [1.1.2] - 2025-07-03

### Added
- **Enhanced Click Functionality**: Improved clickable elements and interaction handling throughout the UI
- **Advanced Object Management**: Enhanced support for GameObject operations and component handling
- **Improved File Operations**: Better file creation, modification, and management capabilities
- **Enhanced Chat Interface**: Improved chat functionality with better message handling and display
- **Debug Logging Utilities**: Added comprehensive debug logging tools and comment utilities for development

### Changed
- **Major UI Improvements**: Significant enhancements to user interface responsiveness and visual feedback
- **Enhanced Model Interface**: Complete redesign of AI model interaction system with improved reliability
- **Optimized Performance**: Major performance improvements in UI rendering and model communication
- **Improved Font Handling**: Better font loading and rendering system with enhanced compatibility
- **Enhanced Image Display**: Improved image visibility and rendering capabilities
- **Streamlined Configuration**: Simplified configuration management and settings persistence

### Fixed
- **Chat Message Processing**: Resolved issues with chat message display and formatting
- **File Creation Bugs**: Fixed various file creation and modification edge cases
- **UI Responsiveness**: Addressed lag and rendering issues in the editor interface
- **Model Communication**: Fixed reliability issues in AI model API communications
- **Memory Management**: Improved memory usage and reduced memory leaks
- **Click Event Handling**: Fixed various click and interaction event processing issues

### Technical Improvements
- Enhanced project indexing service with better performance
- Improved error handling and recovery mechanisms
- Better Unity compatibility across different versions
- Reduced debug log overhead for production builds
- Enhanced code organization and maintainability

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