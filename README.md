# GITMAN

**GITMAN** is a specialized GitHub repository management tool designed specifically for handling documentation files in Markdown format. The project aims to provide a streamlined workflow for managing documentation across multiple GitHub repositories while maintaining strict limitations to prevent any code modifications.

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
- **Markdown Only**: Limited exclusively to Markdown (`.md`) files and related documentation assets
- **Read-Only Code Protection**: Implements strict safeguards to prevent any modifications to source code files
- **Documentation Focus**: Designed specifically for documentation workflows, not development workflows

## Use Cases

- Managing documentation across multiple project repositories
- Synchronizing documentation updates across different repositories
- Maintaining consistent documentation standards across projects
- Handling documentation translations and localization
- Coordinating documentation reviews and approvals
- Offline documentation management with online sync capabilities

## Installation

GITMAN is a single HTML file application that runs in your browser:

1. Download the `gitman.html` file to your local machine
2. Open it in a modern web browser (Chrome, Firefox, Safari, Edge)
3. Enter your GitHub token and username in the configuration section

## Usage

1. **Configuration**:
   - Enter your GitHub token (with appropriate permissions)
   - Enter your GitHub username
   - Optionally load token from a local file

2. **Repository Management**:
   - Click "Load Repositories" to fetch all repositories from your GitHub account
   - Repositories are displayed in accordion format
   - Use the sorting dropdown to organize repositories by name or update date

3. **Documentation Operations**:
   - Expand repository accordions to view documentation files
   - Download documentation from GitHub to local storage
   - Upload documentation from local storage to GitHub
   - View documentation in a separate window

4. **Synchronization**:
   - Use "Sync All Docs" to download all documentation from GitHub
   - Use "Sync Repos" to synchronize online and offline repositories
   - Use "Check Sync Status" to compare local and online repositories

## Contributing

We welcome contributions focused on improving the documentation management capabilities of GITMAN. Please note that all contributions must align with the project's documentation-only focus and must not introduce code editing capabilities.

## License

This project is licensed under [license type] - see the LICENSE file for details.

## Contact

For questions about GITMAN, please contact the project maintainers through the GitHub repository issues.