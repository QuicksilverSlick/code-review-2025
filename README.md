# Code Review 2025 Plugin

Advanced 2025 full-stack architectural audit skill for Claude Code.

## Features

- **OWASP 2025** - Security review against the latest OWASP Top 10
- **MCP Integration** - Verify MCP server context efficiency and tool security
- **Agentic NHI Security** - Check for Non-Human Identity and agent sovereignty risks
- **WCAG 3.0 Silver** - Accessibility audit targeting WCAG 3.0 standards
- **Green Software SCI** - Calculate Software Carbon Intensity metrics

## Installation

### Option 1: Add Marketplace (Recommended)

```bash
/plugin marketplace add YOUR-USERNAME/code-review-2025
/plugin install code-review-2025@code-review-marketplace
```

### Option 2: Direct Install

```bash
/plugin install YOUR-USERNAME/code-review-2025
```

### Option 3: Project-Level

Copy the `code-review-2025/` folder to your project's `.claude/skills/` directory.

## Usage

Once installed, the skill activates when it detects relevant context. You can also use these commands:

| Command | Description |
|:--------|:------------|
| `run code review` | Execute full architectural and security audit |
| `audit agent` | Check for Agentic Sovereignty and NHI risks |
| `mcp check` | Verify MCP server context and tool security |
| `green scan` | Calculate estimated SCI impact |

## Risk Classification

- **🔴 High Risk:** Auth, Crypto, Financials - Mandatory 2-human sign-off
- **🟠 Medium Risk:** MCP Tooling, Database schemas - Security Architect audit
- **🔵 Low Risk:** UI/UX, Local Tests - Automated SAST + Visual Diff

## Reference Files

The skill includes detailed checklists for:

- `references/security-owasp2025.md` - OWASP Top 10 2025 checklist
- `references/frontend.md` - Frontend/React/Next.js standards
- `references/backend.md` - Backend/Serverless standards
- `references/mcp-integration.md` - MCP server security
- `references/agentic-sovereignty.md` - AI agent security
- `references/ai-governance.md` - AI-generated code governance
- `references/iac-devsecops.md` - Infrastructure as Code standards
- `references/green-software.md` - Carbon intensity metrics

## License

MIT
