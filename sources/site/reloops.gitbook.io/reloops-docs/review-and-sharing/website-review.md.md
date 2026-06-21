# Source: https://reloops.gitbook.io/reloops-docs/review-and-sharing/website-review.md

\> For the complete documentation index, see \[llms.txt\](https://reloops.gitbook.io/reloops-docs/llms.txt). Markdown versions of documentation pages are available by appending \`.md\` to page URLs; this page is available as \[Markdown\](https://reloops.gitbook.io/reloops-docs/review-and-sharing/website-review.md).

# Website review

Website review is used for captured web pages that need comments and review decisions.

App route: \`/workspace/:workspaceId/projects/:projectId/assets/:assetId\`

!\[Website review page showing a full-page capture\](/files/3a1a933fe70f96f85c70ba72f2868307ababd2f2)

Use website review when a page, landing page or screenshot-style asset needs feedback in context.

---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the \`ask\` query parameter:

\`\`\`
GET https://reloops.gitbook.io/reloops-docs/review-and-sharing/website-review.md?ask=<question>
\`\`\`

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.