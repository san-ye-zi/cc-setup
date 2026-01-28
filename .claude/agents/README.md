# 🤖 Claude Agents

## 🚀 Quick Start

### 1. Basic Usage

```bash
# Explicit invocation
"Use the <agent-name> agent to review my changes"

# Automatic triggering  
"I need to fix the security vulnerability in the login system"
# → Automatically activates security-auditor

# Agent chaining
"First analyze our architecture, then create tests for the new module"
# → architecture-auditor → test-engineer
```

### 2. Common Patterns

```bash
# Quality Assurance Flow
"Review this PR thoroughly"
# Activates: code-auditor → security-auditor → test-engineer

# New Feature Development
"Set up a new user dashboard feature"  
# Activates: project-architect → test-engineer → integration-manager

# Release Preparation
"Prepare version 2.0 for release"
# Activates: All auditors → release-manager
```
