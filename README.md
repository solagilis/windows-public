# windows-public

<!-- release-manager:download -->
[![Download windows-solagilis 1.0.4](https://img.shields.io/badge/Download-v1.0.4-005FB8?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/solagilis/windows-public/releases/download/v1.0.4/windows-solagilis-win-Setup.exe)

[windows-solagilis-win-Setup.exe](https://github.com/solagilis/windows-public/releases/download/v1.0.4/windows-solagilis-win-Setup.exe) · Windows installer, version 1.0.4
<!-- /release-manager:download -->

<!-- release-manager:about -->
SolAgilis Desktop is a Windows desktop shell for the SolAgilis web application (solagilis.com.br), a site for managing solar power connection requests. It wraps the site in a WebView2-based browser window with native tabs and chrome, and the site drives that chrome directly: it posts its navigation menu, theme colors, user info, and support contact to the shell instead of rendering its own navbar. Beyond browsing, the shell automates filing a project's connection request with the energy distributor's own online portal — filling the form, generating or downloading the required documents, and uploading each one — while leaving the final submission to the user.

## Features
- Renders the SolAgilis site in a tabbed WebView2 window whose navigation bar, colors, and user menu are supplied by the site itself rather than hardcoded in the app.
- Automatically fills out the distributor's connection-request portal from a project's data, without ever pressing submit on the user's behalf.
- Generates and attaches each required document to the portal form, downloading stored files or printing generated pages to PDF as needed.
- Watches the portal after submission to capture the issued protocol number and record it back on the SolAgilis site.
- Prints site documents directly to PDF instead of opening a browser print dialog, and lets the user choose where each file is saved.
- Keeps a single window per environment (local or production), bringing an existing window to the front instead of opening a second one.
- Supports switching between a local development server and the production site via configuration or command-line flags.
- Remembers window position, size, and zoom level between sessions.
<!-- /release-manager:about -->

Releases of windows-solagilis
