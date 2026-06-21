# Source: https://reloops.gitbook.io/reloops-docs/collections-and-presentation/build-and-style-collections.md

\> For the complete documentation index, see \[llms.txt\](https://reloops.gitbook.io/reloops-docs/llms.txt). Markdown versions of documentation pages are available by appending \`.md\` to page URLs; this page is available as \[Markdown\](https://reloops.gitbook.io/reloops-docs/collections-and-presentation/build-and-style-collections.md).

# Build and style collections

Start a collection by choosing where its assets come from.

App route: \`/workspace/:workspaceId/collections/:collectionId\`

!\[Empty collection prompting the user to add source assets\](/files/df2f7ad92577b416c6fa2cc868a30a35aaa9d4af)

Use the source picker to choose a project or folder.

!\[Collection source folder picker\](/files/55686158d558608c80800ebe0510da5b29036b21)

After assets appear, tune the layout for the audience. Internal teams may need dense cards; clients may need a cleaner gallery.

!\[Collection appearance settings popover\](/files/22ded7456680e68f15614c6a02ae417dbf62e3d5)

The finished collection can present selected assets as a visual grid.

!\[Populated Starry Night collection shown as a visual grid\](/files/f21829c2373b2b24efde40c3e548862ad5371fc5)

---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the \`ask\` query parameter:

\`\`\`
GET https://reloops.gitbook.io/reloops-docs/collections-and-presentation/build-and-style-collections.md?ask=<question>
\`\`\`

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.