# EUDI Doc Architecture And Reference Framework

## Project Tags

- `Protocol`

## Overview

EUDI Doc Architecture And Reference Framework is a documentation repository for publishing and exporting structured project documentation with MkDocs and supporting tooling.

## Features

- MkDocs documentation site and structured Markdown content
- Makefile workflow for repeatable local documentation or build tasks

## Tech Stack

- MkDocs
- Make

## Project Structure

- `.github` - project file or directory
- `.gitignore` - project file or directory
- `CHANGELOG` - project file or directory
- `CONTRIBUTING.md` - project file or directory
- `LICENSE` - project file or directory
- `Makefile` - repeatable build or documentation commands
- `SECURITY.md` - project file or directory
- `docs` - documentation source content
- `media` - project file or directory
- `mkdocs.yml` - MkDocs site configuration
- `security` - project file or directory

## Getting Started

### Prerequisites

- Git

### Setup and Run

```bash
git clone https://github.com/ENZOMOTIVE/eudi-doc-architecture-and-reference-framework.git
cd eudi-doc-architecture-and-reference-framework
```

```bash
python3 -m pip install mkdocs
mkdocs serve
```

Use `make`, `make serve`, or `make clean` when the Makefile targets are present and match your workflow.

## Commands

- `mkdocs serve`: preview the documentation site locally.
- `mkdocs build`: generate the static documentation site.
- `make`: run the default Makefile workflow.
- `make clean`: remove generated build artifacts when the target exists.

## Configuration

- Review `mkdocs.yml` before publishing to confirm navigation, theme, and output settings.

## Testing and Quality

- No automated test workflow is declared yet; add tests and document the command here as the project matures.

## Documentation Notes

- Keep this README aligned with the actual source layout and commands.
- Add screenshots, API examples, contract addresses, or deployment links when they become stable.
- Update the project tags when the scope changes.

## Contributing

1. Create a focused branch for the change.
2. Update code and documentation together.
3. Run the relevant checks before opening a pull request.

## License

See the repository license file for usage terms.
