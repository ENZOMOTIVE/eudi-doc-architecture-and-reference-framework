# EUDI Doc Architecture And Reference Framework

> EUDI Doc Architecture And Reference Framework is a documentation publishing workspace for the European Digital Identity Wallet Architecture and Reference Framework.

## The Story

EUDI Doc Architecture And Reference Framework starts with a simple goal: turn project knowledge into a documentation space that can be maintained, previewed, and published with confidence. Its shape tells the same story: the documentation source sits at the center so a maintainer can understand the project before diving into individual files.

## Detailed Description

EUDI Doc Architecture And Reference Framework is a documentation publishing workspace for the European Digital Identity Wallet Architecture and Reference Framework. This README is meant to explain the project like a handoff note: what the idea is, why the repository exists, and how someone can start working with it without opening every file first.

The documentation source is the product here. Navigation, publishing commands, and generated output need to be easy to preview so the docs can evolve without breaking the reader experience.

At the top level, the most important entry points are `.github`, `CHANGELOG`, `CONTRIBUTING.md`, `LICENSE`, `Makefile`, and `SECURITY.md`. Together they show the current boundary of the project and make it easier to separate product code, support files, documentation, and experiments.

The visible stack currently points to `MkDocs` and `Make`. Keep this list honest as the project changes so the README remains useful as a first technical map.

## What It Includes

- Documentation sources that can be previewed, exported, or published.

## How It Is Put Together

| Path | Role |
| --- | --- |
| `.github` | GitHub workflow and repository automation |
| `.gitignore` | ignored local, dependency, and build files |
| `CHANGELOG` | release and change history |
| `CONTRIBUTING.md` | contribution guidelines |
| `LICENSE` | license terms |
| `Makefile` | repeatable local commands |
| `SECURITY.md` | security reporting guidance |
| `docs` | documentation source |
| `media` | static assets and presentation files |
| `mkdocs.yml` | documentation source |
| `security` | project file or folder |

## Local Development

```bash
git clone https://github.com/ENZOMOTIVE/eudi-doc-architecture-and-reference-framework.git
cd eudi-doc-architecture-and-reference-framework
```

For documentation sites, install MkDocs and run `mkdocs serve` to preview the site locally.

## Command Surface

| Area | Commands |
| --- | --- |
| Documentation | `mkdocs serve`, `mkdocs build` |
| Makefile | `make`, `make clean`, and other declared targets |

## Configuration

- Review the documentation navigation and publishing settings before releasing generated docs.

## Quality Checks

- Run `mkdocs build` before publishing documentation changes.

## Where To Take It Next

- Link the published documentation site and keep the local preview command next to the publishing command.
- Keep setup commands current whenever dependencies, scripts, or deployment targets change.
- Record important product decisions here so the repository keeps its story as the code evolves.

## Project Metadata

| Field | Details |
| --- | --- |
| Repository | `ENZOMOTIVE/eudi-doc-architecture-and-reference-framework` |
| Categories | `Protocol` |
| Primary stack | MkDocs, Make |


## License

See the repository license file for usage terms.
