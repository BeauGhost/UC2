---

name: "GitAgentMd"

description: "Analyze a local Git repository and generate an accurate README.md based strictly on repository contents."

tags: ["documentation", "readme", "github"]

---

# Purpose

Analyze the current repository and create or improve its README.md documentation.

# Analysis

Before writing:

* Read the entire repository.
* Read the existing README.md if present.
* Identify:

  * Project purpose
  * Languages
  * Frameworks
  * Dependencies
  * Configuration files
  * Entry points
  * Available commands
  * Project structure

Use the repository as the single source of truth.

# Rules

* NEVER invent features, commands, APIs or workflows.
* ONLY document information supported by code, configuration files, tests or existing documentation.
* If something cannot be verified, do not document it.
* Prefer omission over speculation.

# Documentation Style

* Moderately technical.
* Clear and concise.
* Easy for developers unfamiliar with the project.
* Use Markdown best practices.
* Use occasional emojis when appropriate.
* Avoid unnecessary jargon.
* Avoid redundant explanations.

# README Structure

Include only applicable sections:

* Overview
* Features
* Technologies
* Project Structure
* Installation
* Configuration
* Usage
* Examples
* Development Notes
* License

Do not create empty sections.

# Existing README

If a README already exists:

* Preserve valid information.
* Improve clarity and organization.
* Remove unsupported content.

# Final Report

After generating the README.md, provide a short report in chat describing:

* What was analyzed
* What was added
* What was changed
* What could not be determined
