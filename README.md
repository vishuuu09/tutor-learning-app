# Tutor Learning App

An open-source learning application designed to help learners explore educational content, study books, watch learning videos, and organize their learning experience.

## About the Project

This repository contains a working copy of the open-source **Tutor** project. It is intended for learning, understanding the application architecture, and developing additional features.

The project uses a TypeScript-based application structure with frontend components, server-side modules, content ingestion utilities, and automated tests.

## Features

The existing codebase includes modules for:

- **Learning Dashboard** — Interface for accessing learning content.
- **Books and Documents** — Modules for working with books and educational documents.
- **Video Learning** — Video-related functionality and learning content.
- **AI Tutor** — Tutor-related modules for lessons, questions, and learning support.
- **Content Ingestion** — Utilities for processing and organizing content from supported sources.
- **Server and API** — Backend modules for application functionality.
- **Testing** — Automated tests for application components and features.

*Feature availability may depend on configuration, supported services, and API credentials.*

## Technology Stack

Based on the project configuration and source structure:

- TypeScript
- React
- Vite
- Node.js
- CSS
- Vitest for testing

## Getting Started

### Prerequisites

Install a compatible version of Node.js and npm.

### Installation

Clone this repository:

```bash
git clone https://github.com/vishuuu09/tutor-learning-app.git
cd tutor-learning-app
```

Install the dependencies:

```bash
npm install
```

### Configuration

Review `.env.example` and the project documentation to identify the environment variables and API credentials required for your setup.

Create a local `.env` file if required, and configure the values for the services you intend to use. Never commit API keys, passwords, or other secrets.

### Run the Application

Check the available scripts in `package.json`:

```bash
npm run
```

Use the appropriate development command listed there. For example, if the project defines a `dev` script:

```bash
npm run dev
```

### Run Tests

If the test script is configured:

```bash
npm test
```

Refer to the project configuration for the exact commands supported by your version.

## Project Structure

```text
tutor-learning-app/
├── .github/       # GitHub workflows
├── docs/          # Documentation
├── scripts/       # Utility and build scripts
├── src/
│   ├── app/       # Application components
│   ├── cli/       # Command-line utilities
│   ├── db/        # Database modules
│   ├── ingest/    # Content ingestion
│   ├── epub/      # EPUB processing
│   ├── pdf/       # PDF processing
│   ├── stages/    # Processing stages
│   ├── video/     # Video functionality
│   ├── web/       # Web-related utilities
│   ├── llm/       # Language model integrations
│   ├── server/    # Server-side functionality
│   └── tutor/     # Tutor-related modules
├── test/          # Automated tests
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

## Development and Contributions

This repository is being used to study the existing codebase and develop additional functionality.

As new features are implemented and tested, their purpose, implementation details, and limitations can be documented here.

## Original Project and Attribution

This project is based on the original open-source **Tutor** repository:

https://github.com/demetrius-edelin/tutor

The original project and its authors retain credit for their respective work. This repository maintains the applicable license and attribution notices.

Please refer to the included `LICENSE` file for the terms governing use, modification, and redistribution.

## License

See the [`LICENSE`](LICENSE) file for the applicable license terms.
