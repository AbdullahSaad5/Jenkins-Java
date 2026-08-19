# Jenkins Java

<!-- repo-hygiene: reposhuttle-standard -->

**Minimal Java project for practicing Jenkins CI pipelines.**

## Overview

Minimal Java project for practicing Jenkins CI pipelines.

This README records the repository's purpose, verified local workflow, major technology choices, and maintenance status so the project can be understood without first reverse-engineering the source tree.

## Highlights

- Implementation centered on Java
- Source and supporting project assets kept together for reproducibility

## Tech stack

Java

## Quick start

Clone the repository, then use the build or run instructions provided by the project files.

## Configuration

No repository-specific configuration file is required for the basic workflow documented above.

## Project structure

```text
src/  # primary application source
```

## Repository status

This repository is maintained as a project reference and portfolio artifact.

## Development

Before submitting a change, run the project's available build or execution workflow and verify the affected behavior manually.
Keep changes focused, avoid committing generated artifacts unless the project already tracks them, and update this README whenever setup or behavior changes.

## Security and configuration hygiene

Keep secrets in local environment variables or an ignored `.env` file. Never commit API keys, access tokens, private keys, production database URLs, or customer data. If a credential is committed, revoke and rotate it; deleting the file in a later commit does not remove it from Git history.

## Contributing

Open an issue or provide context before making a large change. Prefer small pull requests with a clear purpose, verification notes, and screenshots for visible UI changes.

## Additional project notes

## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).

## License

No license file is currently included. Unless the repository owner states otherwise, the source is not offered under an open-source license.
