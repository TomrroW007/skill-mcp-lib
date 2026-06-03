# Skill MCP Lib

Welcome to the **Skill MCP Lib** repository. This is a monorepo designed to host and jointly maintain multiple AI Skill libraries and Model Context Protocol (MCP) integrations. By maintaining these libraries in a single, centralized location, we ensure they are well-organized, version-controlled, and ready to be used at any time.

## 📚 Libraries

Our available libraries are located in the `libs/` directory.

### [Superpowers](libs/superpowers/)
The first library in this repository. Superpowers provides a set of composable skills and development methodologies to empower AI coding agents. 

*(For more information, please visit [libs/superpowers/README.md](libs/superpowers/README.md))*

### [Planning With Files](libs/planning-with-files/)
A skill implementing Manus-style persistent markdown planning — the workflow pattern behind the $2B acquisition. 

*(For more information, please visit [libs/planning-with-files/README.md](libs/planning-with-files/README.md))*

## 🤖 AI Agent Guidelines

If you are an AI agent operating within this repository:
- **Root Instructions:** Please refer to `AGENTS.md`, `CLAUDE.md`, or `GEMINI.md` located in the root of this project for routing instructions.
- **Specific Rules:** Always read the specific `RULES.md` or `README.md` within the target library directory (e.g., `libs/superpowers/RULES.md`) before taking any action or writing code.

## 🤝 Adding New Libraries

To add a new Skill or MCP library to this framework:
1. Create a new directory under `libs/` (e.g., `libs/my-new-lib`).
2. Add your skill files, MCP scripts, and documentation inside that folder.
3. Ensure you create a `RULES.md` or `README.md` containing specific guidelines for AI agents interacting with your library.
4. Update this root `README.md` to link to your new library.
