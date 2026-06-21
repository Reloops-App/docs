# Source: https://reloops.gitbook.io/reloops-docs/projects-and-assets/kanban-status-workflow.md

\> For the complete documentation index, see \[llms.txt\](https://reloops.gitbook.io/reloops-docs/llms.txt). Markdown versions of documentation pages are available by appending \`.md\` to page URLs; this page is available as \[Markdown\](https://reloops.gitbook.io/reloops-docs/projects-and-assets/kanban-status-workflow.md).

# Kanban status workflow

### Kanban status workflow

The Kanban view groups project assets by status so producers, reviewers and editors can see progress without opening every asset.

App route: \`/workspace/:workspaceId/projects/:projectId\`

!\[Project Kanban board grouped by asset status\](/files/e3a778aaa1d1c012eac90462c51a9cf1a79f6f1a)

### Common statuses

\* \*\*Needs review\*\* means someone should review the asset.
\* \*\*In Review\*\* means feedback is active.
\* \*\*Approved\*\* means the current version is accepted.

Keep statuses current so the project board remains useful during a review round.

---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the \`ask\` query parameter:

\`\`\`
GET https://reloops.gitbook.io/reloops-docs/projects-and-assets/kanban-status-workflow.md?ask=<question>
\`\`\`

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.