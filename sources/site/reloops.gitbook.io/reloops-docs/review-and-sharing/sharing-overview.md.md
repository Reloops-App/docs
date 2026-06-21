# Source: https://reloops.gitbook.io/reloops-docs/review-and-sharing/sharing-overview.md

\> For the complete documentation index, see \[llms.txt\](https://reloops.gitbook.io/reloops-docs/llms.txt). Markdown versions of documentation pages are available by appending \`.md\` to page URLs; this page is available as \[Markdown\](https://reloops.gitbook.io/reloops-docs/review-and-sharing/sharing-overview.md).

# Sharing overview

Use share links when someone needs to review or receive a specific asset without joining the whole workspace.

App routes: \`/workspace/:workspaceId/projects/:projectId/assets/:assetId\` and \`/share/:token\`

!\[Create Share Link modal for an asset review\](/files/b4d53b1a473940a26bfa264fd2feece471611776)

## Before sending a link

\* Confirm the correct asset and version are open.
\* Choose whether the link should expire.
\* Choose whether downloads are allowed.
\* Send the link only to the intended reviewer.

Use this page when you need the basic sharing model.

For the exact steps and options, continue with \[Create asset share links\](/reloops-docs/review-and-sharing/create-asset-share-links.md).

---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the \`ask\` query parameter:

\`\`\`
GET https://reloops.gitbook.io/reloops-docs/review-and-sharing/sharing-overview.md?ask=<question>
\`\`\`

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.