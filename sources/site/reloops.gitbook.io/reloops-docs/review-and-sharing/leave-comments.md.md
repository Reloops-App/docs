# Source: https://reloops.gitbook.io/reloops-docs/review-and-sharing/leave-comments.md

\> For the complete documentation index, see \[llms.txt\](https://reloops.gitbook.io/reloops-docs/llms.txt). Markdown versions of documentation pages are available by appending \`.md\` to page URLs; this page is available as \[Markdown\](https://reloops.gitbook.io/reloops-docs/review-and-sharing/leave-comments.md).

# Leave comments

## Leave comments

Reloops is built to make feedback clear and actionable. Instead of sending long emails with timestamps, you can leave comments directly on the media itself.

There are three ways to leave comments in Reloops, depending on the type of feedback you need to give.

{% stepper %}
{% step %}

## Timestamp Comments (Single Frame)

This is the standard way to comment on videos.

\* \*\*How to do it:\*\* Pause the video at the exact moment you want to discuss and type your comment in the box.
\* \*\*Result:\*\* The comment is linked to that specific frame. When an editor clicks your comment, the video jumps instantly to that time.

This ensures there is no confusion about which scene or specific moment you are referring to.
{% endstep %}

{% step %}

## Annotations (Anchored Comments)

Annotations allow you to point to a specific part of the screen, like a logo, a color correction issue, or a typo.

\* \*\*How to do it:\*\* Click directly on the video or image in the viewer. A \*\*pin\*\* or \*\*box\*\* will appear where you clicked.
\* \*\*Result:\*\* The comment is visually tied to that spot. Reviewers can see exactly what you are pointing at.

This works on both videos and images.
{% endstep %}

{% step %}

## General Comments

If you want to leave feedback about the asset as a whole (e.g., “Great job, approved!”), you can leave a comment without a timestamp.

\* \*\*How to do it:\*\* Uncheck the timestamp or “Include time” toggle before sending.
\* \*\*Result:\*\* The comment appears in the list but does not move the playhead when clicked.
 {% endstep %}
 {% endstepper %}

## Drawing and Markup tools

When leaving an annotation, you can use drawing tools to be even more precise.

\* \*\*Pen:\*\* Draw freehand circles or arrows.
\* \*\*Arrow:\*\* Point to specific elements.
\* \*\*Rectangle/Circle:\*\* Highlight specific areas.
\* \*\*Colors:\*\* Change the color of your markup to stand out against the video background.

## What to do next

Now that you know how to give feedback, learn about the difference between your workspace and your projects.

Continue with \[Workspaces\](/reloops-docs/workspace-management/workspaces.md) or return to \[Asset review\](/reloops-docs/review-and-sharing/asset-review.md).

---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation dynamically by asking a question.

Perform an HTTP GET request on the current page URL with the \`ask\` query parameter:

\`\`\`
GET https://reloops.gitbook.io/reloops-docs/review-and-sharing/leave-comments.md?ask=<question>
\`\`\`

The question should be specific, self-contained, and written in natural language.
The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.