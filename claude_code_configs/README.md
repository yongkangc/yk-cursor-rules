# Claude Code Configurations

This directory contains non-sensitive configuration files from my Claude Code setup.

## Contents

### settings.json
Main settings file with configuration options:
- `includeCoAuthoredBy`: Controls whether to include co-authored-by information

### agents/
Custom agent definitions for specialized tasks:

- **reviewer.md**: Proactive code review specialist with enhanced security focus and immediate actionable feedback
- **optimizer.md**: Agent for expert-level code performance optimization analysis  
- **tester.md**: Agent for proactive test execution and failure resolution after code changes
- **test-generator.md**: Agent specialized in generating thorough unit tests with edge case coverage (includes tools specification)
- **writer.md**: Agent for creating clear, maintainable technical documentation following Divio's documentation framework
- **refactorer.md**: Agent for improving code structure, readability, and maintainability without changing functionality
- **debugger.md**: Agent for systematic debugging and technical issue resolution

These agents provide specialized expertise for different aspects of software development and can be invoked when needed for focused assistance.

### commands/
Custom slash commands for structured workflows:

- **explore-plan**: Implements "Explore, Plan, Code, Test" workflow for thorough development tasks

## Usage

These configurations demonstrate how to customize Claude Code with:
- Specialized agent personas for different development tasks
- Custom settings for workflow preferences
- Modular agent definitions for reusable expertise
- Structured workflow commands for consistent development processes

## Note

This directory contains only non-sensitive configuration files. Credentials and private settings are excluded.