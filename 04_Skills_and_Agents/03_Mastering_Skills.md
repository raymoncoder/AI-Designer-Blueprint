# 🤖 Part 3: Building AI Skills & Agents

A defining characteristic of a 2026 Product Designer is the ability to build and orchestrate AI "Skills" (specialized agents). You are no longer just a designer; you are an **Agent Orchestrator**.

**What is a Skill?**
A Skill is a pre-configured AI workflow wrapped into an executable command. It runs autonomously in platforms like MCP (Model Context Protocol), Figma, or your IDE.

**Examples of Essential Designer Skills:**
1. **The WCAG Auditor (`/audit-accessibility`)**: Automatically scans a Figma file or a coded component for color contrast, touch targets, and aria-labels.
2. **The UX Writer (`/rewrite-ux-copy`)**: Translates generic wireframe text into concise, brand-aligned, conversion-optimized microcopy.
3. **The Edge-Case Finder (`/stress-test-flow`)**: Analyzes a user flow and generates a list of 20 potential failure points (e.g., "What if the API times out here?").

**How to Build a Skill in 2026:**
1. **Define the Trigger:** What user action or command starts the agent?
2. **Provide the System Prompt:** "You are an expert UX Writer. Always use active voice. Limit buttons to 2 words."
3. **Connect the Tools (MCP):** Give the agent access to read Figma files, search Jira tickets, or run local Python scripts.
4. **Publish to the Team Repo:** Share the Skill via your team's internal AI hub so developers and PMs can use it too.
