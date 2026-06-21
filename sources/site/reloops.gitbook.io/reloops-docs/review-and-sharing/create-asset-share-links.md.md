# Source: https://reloops.gitbook.io/reloops-docs/review-and-sharing/create-asset-share-links.md

\> For the complete documentation index, see \[llms.txt\](https://reloops.gitbook.io/reloops-docs/llms.txt). Markdown versions of documentation pages are available by appending \`.md\` to page URLs; this page is available as \[Markdown\](https://reloops.gitbook.io/reloops-docs/review-and-sharing/create-asset-share-links.md).

# Create asset share links

An asset share link is the simplest way to send one asset for review.

Open the asset, select \*\*Share\*\*, then create the link.

App route: \`/workspace/:workspaceId/projects/:projectId/assets/:assetId\`

!\[Create Share Link modal for an asset review\](/files/b4d53b1a473940a26bfa264fd2feece471611776)

### Common link settings

\* Lock the link to the current version.
\* Add an expiration date when access should end.
\* Allow or block downloads based on the review need.

Locking the link to the current version helps reviewers see the exact version you intended to send.

Public share route: \`/share/:token\`

---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the \`ask\` query parameter:

\`\`\`
GET https://reloops.gitbook.io/reloops-docs/review-and-sharing/create-asset-share-links.md?ask=<question>
\`\`\`

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.