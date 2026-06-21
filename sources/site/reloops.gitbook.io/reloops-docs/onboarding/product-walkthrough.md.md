# Source: https://reloops.gitbook.io/reloops-docs/onboarding/product-walkthrough.md

\> For the complete documentation index, see \[llms.txt\](https://reloops.gitbook.io/reloops-docs/llms.txt). Markdown versions of documentation pages are available by appending \`.md\` to page URLs; this page is available as \[Markdown\](https://reloops.gitbook.io/reloops-docs/onboarding/product-walkthrough.md).

# Product walkthrough

Use this walkthrough when you want the shortest visual map of the product.

Use \[Getting started\](/reloops-docs/onboarding/getting-started.md) when you want the first setup flow.

Routes use placeholders such as \`:workspaceId\`, \`:projectId\`, \`:assetId\` and \`:collectionId\`.

\*\*\*

## Workspaces

Choose the workspace you want to work in.

App route: \`/workspaces\`

!\[Workspaces page showing multiple workspace cards and the New Workspace button\](/files/91eedc5556e169c0bf6fbc630a20f96478d3ca9f)

\*\*\*

## Projects

Projects hold the files and review progress for a body of work.

App route: \`/workspace/:workspaceId/projects\`

!\[Projects page showing project cards and the New Project button\](/files/03f9feea8692a2e9a2c49802a2a2a8e65eeaddf5)

\*\*\*

## Create a project

Create a project from a template or start empty.

App route: \`/workspace/:workspaceId/projects\`

!\[Create New Project modal with the Social Media template selected\](/files/b495e157d2e9c6f12d01f661d9d7443da5fecad8)

\*\*\*

## Project assets

Use the Assets view to upload files and open them for review.

App route: \`/workspace/:workspaceId/projects/:projectId\`

!\[Project assets page with the Upload menu open\](/files/73e2f664c46955ef84c40ca97b03fd6cb3be6439)

\*\*\*

## Kanban status

Use Kanban to track asset progress by status.

App route: \`/workspace/:workspaceId/projects/:projectId\`

!\[Project Kanban board grouped by asset status\](/files/e3a778aaa1d1c012eac90462c51a9cf1a79f6f1a)

\*\*\*

## Reviewers and links

Use these tabs to manage reviewers and active share links.

App route: \`/workspace/:workspaceId/projects/:projectId\`

!\[Project reviewers tab showing a guest reviewer and assigned asset\](/files/9370b5950f106fd41a23a8a3070bec5749185ae7)

!\[Project links tab showing an active asset share link\](/files/9353da8b890d569167600ee5c756aad9e2b6d17e)

\*\*\*

## Collections

Collections present selected assets without moving the source files.

App routes: \`/workspace/:workspaceId/collections\` and \`/workspace/:workspaceId/collections/:collectionId\`

!\[Empty collection prompting the user to add source assets\](/files/df2f7ad92577b416c6fa2cc868a30a35aaa9d4af)

!\[Collection source folder picker\](/files/55686158d558608c80800ebe0510da5b29036b21)

!\[Collection appearance settings popover\](/files/22ded7456680e68f15614c6a02ae417dbf62e3d5)

!\[Populated Starry Night collection shown as a visual grid\](/files/f21829c2373b2b24efde40c3e548862ad5371fc5)

\*\*\*

## Asset review

Open an asset to comment, assign, approve or request changes.

App route: \`/workspace/:workspaceId/projects/:projectId/assets/:assetId\`

!\[Asset review page with a timestamped comment and request revision controls\](/files/bf717f7d2a320db8507358873102d86dfdfeecc6)

\*\*\*

## Share an asset

Use a share link when one file needs focused external review.

App routes: \`/workspace/:workspaceId/projects/:projectId/assets/:assetId\` and \`/share/:token\`

!\[Create Share Link modal for an asset review\](/files/b4d53b1a473940a26bfa264fd2feece471611776)

\*\*\*

## Compare versions

Compare mode shows two versions side by side.

App route: \`/workspace/:workspaceId/projects/:projectId/assets/:parentAssetId/compare\`

!\[Compare Versions page showing two video versions side by side\](/files/6feea90c76fc922ba0d5782c0741d1adf6f0206a)

\*\*\*

## Website review

Website review uses the same review surface for captured pages.

App route: \`/workspace/:workspaceId/projects/:projectId/assets/:assetId\`

!\[Website review page showing a full-page capture\](/files/3a1a933fe70f96f85c70ba72f2868307ababd2f2)

\*\*\*

## Notifications, team and settings

Use these areas to track activity and manage the workspace.

App routes: \`/workspace/:workspaceId/teams\` and \`/workspace/:workspaceId/settings\`

!\[Notifications panel showing review activity and file updates\](/files/d3923493e776e183dbb1218e34ea73a1a91c2788)

!\[Team management page showing AI agents and organization members\](/files/fc29b1700d169318f6c5227d67bd604a4e1fbc08)

!\[Workspace settings page showing profile, billing limits and storage\](/files/9988fe1a1d82cb3b498b578b49332aa29afe47bb)

---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the \`ask\` query parameter:

\`\`\`
GET https://reloops.gitbook.io/reloops-docs/onboarding/product-walkthrough.md?ask=<question>
\`\`\`

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.