# Source: https://reloops.gitbook.io/reloops-docs/review-and-sharing/asset-review.md

\> For the complete documentation index, see \[llms.txt\](https://reloops.gitbook.io/reloops-docs/llms.txt). Markdown versions of documentation pages are available by appending \`.md\` to page URLs; this page is available as \[Markdown\](https://reloops.gitbook.io/reloops-docs/review-and-sharing/asset-review.md).

# Asset review

### Asset review

The asset review page keeps feedback and decisions attached to the asset being reviewed.

App route: \`/workspace/:workspaceId/projects/:projectId/assets/:assetId\`

!\[Asset review page with a timestamped comment and request revision controls\](/files/bf717f7d2a320db8507358873102d86dfdfeecc6)

### What you can do from review

\* View the current asset version.
\* Leave or read comments.
\* Assign the asset to a teammate.
\* Change the review status.
\* Approve the current version or request revisions.
\* Share the asset with a reviewer.

---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the \`ask\` query parameter:

\`\`\`
GET https://reloops.gitbook.io/reloops-docs/review-and-sharing/asset-review.md?ask=<question>
\`\`\`

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.