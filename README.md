# Claude Code Plugins

My personal Claude Code plugins. These plugins provide a set of agents, commands, skills and MCP servers to help you with your development workflow.

## Quick Install

```bash
# Step 1: Add the marketplace
/plugin marketplace add krzko/claude-code-plugins

# Step 2: Install the plugin
/plugin install claude-code-plugins
```

## What's Inside

### 📋 Development Commands

- `/new-task` - Analyse code for performance issues
- `/code-explain` - Generate detailed explanations
- `/code-optimise` - Performance optimisation
- `/code-cleanup` - Refactoring and cleanup
- `/feature-plan` - Feature implementation planning
- `/lint` - Linting and fixes
- `/docs-generate` - Documentation generation

### 🔌 API Commands

- `/api-new` - Create new API endpoints
- `/api-test` - Test API endpoints
- `/api-protect` - Add protection & validation

### 🎨 UI Commands

- `/component-new` - Create React components
- `/page-new` - Create Next.js pages

### 💾 Supabase Commands

- `/types-gen` - Generate TypeScript types
- `/edge-function-new` - Create Edge Functions

### 🤖 Specialised AI Agents

**Architecture & Planning**
- **tech-stack-researcher** - Technology choice recommendations with trade-offs
- **system-architect** - Scalable system architecture design
- **backend-architect** - Backend systems with data integrity & security
- **frontend-architect** - Performant, accessible UI architecture
- **requirements-analyst** - Transform ideas into concrete specifications

**Code Quality & Performance**
- **refactoring-expert** - Systematic refactoring and clean code
- **performance-engineer** - Measurement-driven optimisation
- **security-engineer** - Vulnerability identification and security standards

**Documentation & Research**
- **technical-writer** - Clear, comprehensive documentation
- **learning-guide** - Teaching programming concepts progressively
- **deep-research-agent** - Comprehensive research with adaptive strategies

## Installation

### From GitHub (Recommended)

```bash
# Add marketplace
/plugin marketplace add krzko/claude-code-plugins

# Install plugin
/plugin install claude-code-plugins
```

### From Local Clone (for development)

```bash
git clone https://github.com/krzko/claude-code-plugins.git
cd claude-code-plugins

# Add as local marketplace
/plugin marketplace add /path/to/claude-code-plugins

# Install plugin
/plugin install claude-code-plugins
```

## Best For

- Next.js developers
- TypeScript projects
- Supabase users
- React developers
- Full-stack engineers

## Usage Examples

### Planning a Feature

```bash
/feature-plan
# Then describe your feature idea
```

### Creating an API

```bash
/api-new
# Claude will scaffold a complete API route with types, validation, and error handling
```

### Research Tech Choices

Just ask Claude questions like:
- "Should I use WebSockets or SSE?"
- "How should I structure this database?"
- "What's the best library for X?"

The tech-stack-researcher agent automatically activates and provides detailed, researched answers.

## Philosophy

This setup emphasises:
- **Type Safety**: Never uses `any` types
- **Best Practices**: Follows modern Next.js/React patterns
- **Productivity**: Reduces repetitive scaffolding
- **Research**: AI-powered tech decisions with evidence

## Requirements

- Claude Code 2.0.13+
- Works with any project (optimised for Next.js + Supabase)

## Customisation

After installation, you can customise any command by editing files in `.claude/commands/` and `.claude/agents/`.
