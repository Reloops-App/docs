# Source: https://reloops.gitbook.io/reloops-docs/workspace-management/team-and-workspace-settings.md

\> For the complete documentation index, see \[llms.txt\](https://reloops.gitbook.io/reloops-docs/llms.txt). Markdown versions of documentation pages are available by appending \`.md\` to page URLs; this page is available as \[Markdown\](https://reloops.gitbook.io/reloops-docs/workspace-management/team-and-workspace-settings.md).

# Team and workspace settings

### Team and workspace settings

Workspace admins can review team access, AI agents, workspace identity and organization limits from the team and settings areas.

Team route: \`/workspace/:workspaceId/teams\`

!\[Team management page showing AI agents and organization members\](/files/fc29b1700d169318f6c5227d67bd604a4e1fbc08)

Workspace settings route: \`/workspace/:workspaceId/settings\`

!\[Workspace settings page showing profile, billing limits and storage\](/files/9988fe1a1d82cb3b498b578b49332aa29afe47bb)

### Before changing settings

\* Confirm you are in the correct workspace.
\* Check whether the setting affects the whole team.
\* Review storage, user and workspace limits before adding more workspaces or members.

---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the \`ask\` query parameter:

\`\`\`
GET https://reloops.gitbook.io/reloops-docs/workspace-management/team-and-workspace-settings.md?ask=<question>
\`\`\`

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.