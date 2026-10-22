[Home](../../README.md) · [Docs](../README.md)

# Maintaining this knowledge base

**Owner resources.** These instructions and templates help maintain the repository. They are not evidence about Minh Quan's background, experience, or preferences.

| I want to… | Use this |
|---|---|
| Fill gaps through a conversation with AI | [Owner interview](interview.md) |
| Document a project | [Project template](project-template.md) |
| Document a role or other experience | [Experience template](experience-template.md) |

## Update the source, then the links

Keep each detailed fact in one main page. Other pages can summarize it and link to that page.

| Change | What to update |
|---|---|
| A project or role changes | Update its detail page, evidence links, and review date. |
| A skill gains supporting evidence | Link the [skills page](../skills/README.md) to the relevant project or experience. |
| An FAQ answer changes | Keep the answer short and link to the updated source page. |
| Availability or another changing detail changes | State the date the information applies to, separately from the editorial review date. |
| A new page is added | Add parent links and update its section README and the [complete docs index](../README.md). |
| A new folder is added | Give it a README that explains the topic and links to its children. |

Add `Last reviewed: YYYY-MM-DD` to factual pages after reviewing their contents. This is an editorial review date; it does not establish a project start date, live deployment status, or current availability. Confirm those facts separately before describing them as current.

## Grow a section when it needs more room

Start with the section README. Move a substantial project, role, or topic into its own page when it benefits from a separate explanation. Use descriptive lowercase names, such as `projects/project-slug/README.md` or `experience/role-slug.md`.

Keep the repository root limited to `README.md` and `docs/`. Use relative links for navigation within this repository, including the root README. Keep full URLs in copyable AI prompts, for external resources, and for pinned historical source citations. Give every folder a README. Keep this owner guide separate from the visitor reading path.

<details>
<summary>Presentation and publishing checklist</summary>

- Keep summaries, contributions, outcomes, dates, and navigation visible.
- Use short tables with two or three columns and one level of `<details>` sections.
- Put blank lines around Markdown inside `<details>`.
- Review AI drafts before publishing new biographical claims; remove unused template fields.
- Describe missing information as not documented rather than guessing.
- Check links, anchors, table width, and collapsible sections in GitHub's rendered view.
- Try the root AI prompt: the response should suggest exactly three grounded questions and cite actual sources.
- Ask something the published content does not answer; the AI should acknowledge the gap.
- Confirm that this folder's instructions and templates are not used as biography.

</details>

Last updated: 2026-10-22
