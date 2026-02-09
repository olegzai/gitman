# GITMAN

**GITMAN** is a specialized GitHub repository management tool designed specifically for handling documentation files in Markdown format. The project aims to provide a streamlined workflow for managing documentation across multiple GitHub repositories while maintaining strict limitations to prevent any code modifications.

## Table of Contents

- [Purpose](#purpose)
- [Features](#features)
- [Limitations](#limitations)
- [Use Cases](#use-cases)
- [Target Audience Insights](#target-audience-insights)
- [Development Approach](#development-approach)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Configuration](#configuration)
- [Commands](#commands)
- [Security](#security)
- [Architecture](#architecture)
- [Testing](#testing)
- [Versioning](#versioning)
- [Support](#support)
- [Contributing](#contributing)
- [License](#license)
- [Roadmap](#roadmap)

## Purpose

GITMAN serves as a documentation-focused repository manager that allows users to efficiently handle Markdown files across multiple GitHub repositories. The tool is intentionally limited to documentation management to ensure safe and focused operations without the risk of unintended code changes.

## Features

- **Markdown Documentation Management**: Efficiently manage `.md` files across multiple GitHub repositories
- **Safe Operations**: Strictly limited to documentation files to prevent accidental code modifications
- **Multi-repository Support**: Handle documentation across multiple GitHub repositories simultaneously
- **Version Control Integration**: Seamless integration with GitHub's version control system for documentation
- **Documentation Workflow Optimization**: Streamlined processes for updating, reviewing, and publishing documentation
- **Local and Online Synchronization**: Sync documentation between local storage and GitHub repositories
- **Repository Status Tracking**: Visual indicators for synchronization status
- **File Filtering**: Automatically identifies and displays only documentation files (MD files)
- **Accordions Interface**: Hierarchical accordion-based UI for easy navigation
- **Sorting Options**: Sort repositories by name or last update date
- **Token Management**: Secure token handling with file loading capability
- **Bulk Operations**: Sync all documentation or all repositories at once
- **Responsive Design**: Minimalist, mobile-friendly interface that works on all screen sizes
- **Grid Layout**: Organized grid layout for documentation files
- **Touch-Friendly**: Optimized for touch devices with appropriately sized elements

## Limitations

- **No Code Editing**: GITMAN cannot and will never be able to edit code files (`.js`, `.py`, `.java`, `.cpp`, etc.)
- **Markdown Only**: Limited exclusively to Markdown and Text (`.md`, `.txt`) files and related documentation assets
- **Read-Only Code Protection**: Implements strict safeguards to prevent any modifications to source code files
- **Documentation Focus**: Designed specifically for documentation workflows, not development workflows

## Use Cases

- Managing documentation across multiple project repositories
- Synchronizing documentation updates across different repositories
- Maintaining consistent documentation standards across projects
- Handling documentation translations and localization
- Coordinating documentation reviews and approvals
- Offline documentation management with online sync capabilities

## Target Audience Insights

Based on user feedback, GITMAN is designed for users who:

- Primarily manage 11-25 repositories with documentation (though options exist for different scales)
- Update documentation on a daily or weekly basis
- Place high importance on security, ensuring no code changes occur accidentally
- Focus on documentation management rather than code editing
- Utilize features like:
  - Markdown documentation management
  - Multi-repository support
  - Version control integration
  - Local and online synchronization
  - Repository status tracking
  - File filtering
  - Accordion-based navigation
  - Sorting capabilities
  - Responsive design for mobile devices
  - Visual status indicators
- Require bulk operations for efficient management of multiple repositories simultaneously:
  - Synchronize all documentation at once
  - Synchronize all repositories at once
  - Update all repositories simultaneously
  - Review all changes across repositories at once
- Work primarily with Markdown and plain text files, sometimes with embedded code snippets
- Need additional features like search capabilities, filtering options, collaboration tools, change tracking, and export/import functionality
- Face challenges with synchronizing documents across repositories, maintaining consistent formatting, and tracking changes and updates
- Appreciate the use of TypeScript for development due to its type safety benefits
- Have positive attitudes toward the tool's limitations (Markdown/text only) and inability to edit code files
- Value offline documentation management capabilities

## Development Approach

- **Technology Stack**: Built with TypeScript to ensure type safety and maintainability
- **Frontend Framework**: Vue.js for building reactive and component-based user interfaces
- **Build Tool**: Vite for fast development and optimized builds
- **Testing Framework**: Vitest for rapid unit testing with Vite integration
- **Code Quality**: Biome for unified code formatting and linting
- **GitHub Integration**: Octokit for reliable interaction with GitHub APIs
- **API Usage**: Integration with both REST and GraphQL APIs for optimal GitHub functionality
- **Architecture**: Serverless application designed to run without dedicated servers
- **Hosting**: Deployable on GitHub Pages, Netlify, Vercel, and similar hosting services
- **Security**: Tokens can be handled via environment variables or stored in configuration files with file loading capability
- **User Preferences**: Supports both file-based token loading and manual entry based on user preference
- **Offline Capability**: Critical for users who need to work offline regularly
- **Interface Design**: Prioritizes accordion-based navigation, responsive design, visual status indicators, and sorting capabilities
- **Documentation Formats**: Optimized for Markdown (.md) and plain text (.txt) files, with support for embedded code snippets

## Installation

GITMAN can be installed in multiple ways depending on your preference:

- Install globally via npm: `npm install -g gitman`
- Download the executable file for your platform
- Clone the repository and install dependencies locally

### System Requirements

GITMAN is designed to run in a browser environment, making it accessible across platforms without complex installations.

## Getting Started

1. Initialize GITMAN with the command: `gitman init`
2. Configure your GitHub token for repository access
3. Add repositories you wish to manage: `gitman add <repository-url>`
4. Synchronize your documentation: `gitman sync`

## Configuration

GITMAN supports various configuration options:

- Local repository paths
- File types to synchronize
- Automatic synchronization frequency
- File filtering parameters
- Configuration is stored in a `.gitman` file in your working directory

## Commands

GITMAN provides several commands for efficient management:

- `gitman sync`: Synchronize documentation across repositories
- `gitman list`: List all managed repositories
- `gitman add <repository>`: Add a new repository to manage
- `gitman remove <repository>`: Remove a repository from management

## Security

For GitHub token authorization, GITMAN requires:

- Full access to repositories (for both public and private repositories)
- Access to private repositories specifically

## Architecture

GITMAN follows a multi-platform architecture:

- Single Page Application (SPA) for web interface
- Traditional web application backend
- Command Line Interface (CLI) tool
- Progressive Web App (PWA) capabilities

## Testing

GITMAN employs multiple testing strategies:

- Unit testing
- Integration testing
- End-to-end (E2E) testing
- Manual testing

## Versioning

GITMAN uses Semantic Versioning (SemVer) for release management, with updates released as needed based on user feedback and feature requirements.

## Support

If you need help with GITMAN, you can:

- Open an issue on GitHub Issues
- Consult the documentation on the website

## Contributing

While contributions are welcome, GITMAN is currently developed by a single developer. Future updates may include community contribution options.

## License

GITMAN is released under the MIT License.

## Roadmap

Planned future enhancements include:

- Collaborative editing for documentation
- Documentation change history tracking
