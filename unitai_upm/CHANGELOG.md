# Changelog

All notable changes to this project will be documented in this file.

## [1.1.6] - 2025-07-13

### Added
- **Scene View Camera Control**: Added the ability for the AI to programmatically control the Scene View camera, enabling actions like panning, zooming, and rotating to focus on specific objects or areas.

### Changed
- **Performance Tuning**: Significantly improved performance of the asset post-processor by optimizing background thread usage for embedding updates.

### Fixed
- **Index Stats Display**: Resolved an issue where documentation index statistics were not correctly loaded and displayed in the configuration window.

## [1.1.5] - 2025-07-10

### Added
- **Enhanced GameObject Search**: Added support for limiting GameObject searches to specific hierarchy paths for more precise results
- **File Move Operations**: Enhanced file move operations with improved destination directory handling

### Changed
- **Production API Configuration**: Switched back to production API configuration from local development environment
- **Improved SVG File Detection**: Enhanced SVG file detection to support both XML and SVG language types for better file handling
- **Unity 2022 Compatibility**: Added specific compatibility fixes for Unity 2022 toolbar display issues

### Fixed
- **SVG Rendering**: Fixed SVG file detection and rendering with improved language type recognition
- **Unity Version Compatibility**: Resolved toolbar display issues specifically affecting Unity 2022 users
- **GameObject Hierarchy Search**: Improved accuracy of GameObject search operations with path-based filtering

### Technical Improvements
- Enhanced model interface with improved search and move operation capabilities
- Improved UI helper functions with better cross-Unity version compatibility
- Refined configuration management for production deployment

## [1.1.4] - 2025-07-09

### Added
- **Drag & Drop GameObject Support**: Revolutionary new feature allowing GameObjects to be dragged directly from the Hierarchy into the chat input, automatically inserting their scene paths for precise AI assistance
- **SVG File Display Support**: Added native support for viewing and displaying SVG files within the interface
- **Advanced Documentation Search**: Integrated Lucene.NET search engine for powerful Unity documentation indexing and retrieval capabilities
- **Screenshot Integration**: Enhanced screenshot capture functionality with better file management and attachment workflow

### Changed
- **Increased System Limits**: Significantly increased various system limits for better performance with larger projects and files
- **Enhanced File Management**: Improved file processing, validation, and error handling across all file operations
- **UI Responsiveness Improvements**: Better handling of drag-and-drop events and visual feedback during file operations
- **Copy Functionality Enhancements**: Improved copy operations and file duplication handling
- **Input Area Enhancements**: Better text input handling with improved focus management and caret positioning
- **Performance Optimizations**: Optimized file processing and UI rendering for better responsiveness with large file sets

### Fixed
- **File Removal Operations**: Resolved issues with file removal and cleanup operations
- **Drag & Drop Edge Cases**: Fixed various edge cases in drag-and-drop functionality and event handling
- **Focus Management**: Improved text input focus handling during streaming operations and user interactions
- **Memory Management**: Better cleanup of temporary files and cached data during file operations
- **UI Layout Issues**: Fixed various layout and positioning issues in the file attachment areas

### Technical Improvements
- **Fast index Integration**: Complete integration fast index for advanced search and indexing capabilities
- **Enhanced File Processing Pipeline**: Redesigned file processing architecture for better reliability and performance
- **Improved Event Handling**: Better separation of drag-and-drop events for different UI areas
- **Code Organization**: Better modularization of file management and UI helper functions
- **Unity Compatibility**: Enhanced compatibility across different Unity versions with better feature detection

## [1.1.3] - 2025-07-05

### Added
- **Enhanced Console Logging System**: Complete overhaul of logging infrastructure with new classes for better debug information and log management
- **Advanced UI Helper Functions**: New utility functions for improved UI management and better code organization
- **Directory Creation Improvements**: Enhanced directory handling and creation capabilities
- **Log Persistence**: Added ability to save and manage console logs for better debugging experience

### Changed
- **Improved Syntax Highlighting**: Enhanced C# syntax highlighting performance and reliability
- **UI Scroll Behavior**: Major improvements to scrolling behavior, eliminated unwanted jumps and enhanced smooth scrolling
- **Model Interface Optimization**: Refined model interface communication with better error handling and response processing
- **Configuration Management**: Enhanced configuration system with improved settings persistence
- **Code Organization**: Better separation of concerns with UI helper functions moved to dedicated classes

### Fixed
- **UI Scroll Jumps**: Resolved issues with unexpected UI scrolling and jumping behavior
- **Syntax Highlighting Glitches**: Fixed various syntax highlighting rendering issues
- **Log Display**: Improved log display consistency and reliability
- **Multiple File Operations**: Enhanced handling of multiple file operations and directory management
- **UI Responsiveness**: Fixed various UI responsiveness issues during intensive operations

### Technical Improvements
- Enhanced logging architecture with structured log entries
- Improved code maintainability through better class organization
- Better error handling and debugging capabilities
- Optimized UI rendering performance
- Enhanced Unity editor integration stability

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