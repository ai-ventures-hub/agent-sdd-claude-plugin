# Agent-SDD Claude Plugin

Agent-SDD framework for structured software development with 16 specialized sub-agents, automated analytics, living architecture diagrams, and framework resilience capabilities.

## Installation

To add this marketplace to Claude Code:

```bash
/plugin marketplace add ai-ventures-hub/agent-sdd-claude-plugin
```

Then install the Agent-SDD framework:

```bash
/plugin install agent-sdd-framework
```

## Features

- **16 Specialized Sub-Agents**: Each agent handles specific aspects of the development lifecycle
- **Automated Analytics**: JSON Lines logging with performance tracking and trend analysis
- **Living Architecture Diagrams**: Auto-generated Mermaid diagrams that evolve with your codebase
- **Framework Resilience**: Self-healing capabilities with corruption detection
- **Multi-Platform Support**: Auto-adapts to Claude, Grok, and Codex platforms

## Usage

The Agent-SDD framework is triggered by the `sdd-task` command:

```bash
# Initialize a new project
sdd-task --init

# Design phase with specifications
sdd-task --design SPEC-001

# Development phase
sdd-task --develop SPEC-001

# Execute tests
sdd-task --execute SPEC-001

# Improve existing features
sdd-task --improve SPEC-001

# Bootstrap new projects
sdd-task --bootstrap

# Evolve framework based on analytics
sdd-task --evolve
```

## Specialized Agents

- **project_analyzer**: Analyze existing project structure
- **task_decomposer**: Break complex specs into manageable tasks
- **designer**: Create wireframes and user journeys
- **test_runner**: Execute and analyze test results
- **code_reviewer**: Enforce quality standards
- **analytics_collector**: Track usage patterns
- **architecture_visualizer**: Generate architecture diagrams
- And 9 more specialized agents...

## Documentation

Full documentation is available in the `.claude/docs/` directory after installation.

## Support

- **Author**: AI Ventures
- **Email**: info@agent-sdd.com
- **Repository**: https://github.com/ai-ventures-hub/agent-sdd-claude-plugin

## License

MIT License - See LICENSE file for details