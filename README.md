# VEXplorer

A browser-based documentation explorer for VEX Robotics APIs, powered by the [vexmcp.ct839.com](https://vexmcp.ct839.com) backend.

## Features

- **Search** VEX documentation across all platforms and languages
- **Filter** by platform (VEX IQ Gen 2, VEX V5, PROS, LemLib) and language (Python, C++)
- **Get API Docs** — look up any specific API by name with auto-detect for platform/language
- **Detail view** — signature, starter code, learning objectives, suggested prompts, and tags
- **Quick searches** for common VEX APIs

## Live Site

[https://andymaker156.github.io/VEXplorer/](https://andymaker156.github.io/VEXplorer/)

## Usage

Open the live site in any browser. No installation required — it's a single HTML file.

- Type a query (e.g. `Motor.spin`, `Brain.Battery`) in the search bar and press Enter or click **Search**
- Use the sidebar to filter by platform and language
- Click on any result card to see full API details
- Switch to the **Get API Docs** tab to look up a specific API by exact name

## Backend

All documentation data is served by the MCP backend at `https://vexmcp.ct839.com/mcp`.
