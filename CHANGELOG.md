# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2025-11-27

### Initial Release

#### Added
- Complete email builder with React DnD integration
- MJML conversion for production-ready HTML emails
- Drag-and-drop components: Text, Button, Image, Divider, Spacer, Columns
- Property editor for real-time component customization
- Pre-built templates: Newsletter, Welcome, Promotional
- TypeScript support with full type definitions
- UMD bundle for CDN usage
- `useEmailBuilder` React hook for state management
- Responsive email template support

#### Features
- **@emailbuilder-v1/core** - Core MJML conversion and types
- **@emailbuilder-v1/react** - React components and UI
- **react-dnd** - Bundled drag-and-drop dependencies
- ESM and CommonJS module support
- CDN deployment at static.gooups.dev

#### Package Structure
- Single install includes all dependencies
- Re-exports from core and react packages
- Convenient DndProvider and HTML5Backend exports

---

**Legend:**
- `Added` for new features
- `Changed` for changes in existing functionality
- `Deprecated` for soon-to-be removed features
- `Removed` for now removed features
- `Fixed` for any bug fixes
- `Security` for vulnerability fixes
