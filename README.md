# NUS AI Society Website Content

This repository contains the dynamic content for the [NUS SoC AI Society Website](https://github.com/NUSAISoc/aisoc-website).

## Content Types

We have three types of content, organized into directories:

- `/blog`: Blog posts and articles.
- `/events`: Information about upcoming and past events.
- `/team`: Profiles for the society's team. Each entry has a `category` of `exco` (current executive committee), `member` (current member), or `alumni` (past exco/member).

## How to Add Content

1. Navigate to the appropriate folder (`blog`, `events`, or `team`).
2. Copy the corresponding `_template-*.md` file.
3. Rename the new file to a descriptive slug (e.g., `my-new-blog-post.md`). **Important: Ensure your filename does not begin with `_template-`.**
4. Fill in the YAML frontmatter (the metadata between the `---` blocks at the top of the file) and write your content below it.
5. Commit and push your changes to the `main` branch.

The main website will automatically pull the latest changes from the `main` branch during its build process.

## Formatting Guidelines

- All files must strictly adhere to the YAML frontmatter structure defined in the templates. Missing required fields will cause the website build to fail.
- Use standard Markdown formatting for the content.
- Ensure any dates follow the ISO 8601 format (e.g., `2026-03-15T14:00:00Z`).
