# Lorite Obsidian Clipper Templates

A curated collection of Obsidian Web Clipper templates for capturing web content into structured notes.

These templates are designed for real-world knowledge workflows: articles, GitHub work, AI chats, email, social content, videos, and tasks.

## Repository Structure

- [LICENSE](LICENSE)
- [templates/](templates/)

## Template Catalog

### Articles and Websites

- [Article (ALREADY READ)](templates/01-article-(already-read)-clipper.json)
- [Article fullHtml (ALREADY READ)](templates/02-article-fullhtml-(already-read)-clipper.json)
- [Article (TODO READ)](templates/03-article-(todo-read)-clipper.json)
- [Website Default](templates/04-website-default-clipper.json)
- [Website contentHtml](templates/05-website-contenthtml-clipper.json)
- [Website fullHtml](templates/06-website-fullhtml-clipper.json)
- [Wikipedia](templates/28-wikipedia-clipper.json)

### Tasks

- [TASK](templates/07-task-clipper.json)
- [TASK - GitHub Issue](templates/08-task---github-issue-clipper.json)

### Social and Community

- [Reddit Post](templates/09-reddit-post-clipper.json)
- [The Hacker News](templates/26-the-hacker-news-clipper.json)
- [Instagram](templates/29-instagram-clipper.json)
- [LinkedIn](templates/30-linkedin-clipper.json)

### Shopping and Places

- [Product](templates/10-product-clipper.json)
- [Recipes](templates/25-recipes-clipper.json)
- [Google Maps](templates/27-google-maps-clipper.json)

### Video and Learning

- [YouTube with transcript](templates/11-youtube-with-transcript-clipper.json)
- [YouTube](templates/12-youtube-clipper.json)
- [YouTube timestamp](templates/13-youtube-timestamp-clipper.json)
- [Jupyter Notebook](templates/24-jupyter-notebook-clipper.json)

### AI and LLM Platforms

- [Google NotebookLM](templates/14-google-notebooklm-clipper.json)
- [Google Gemini](templates/15-google-gemini-clipper.json)
- [Grok](templates/16-grok-clipper.json)
- [ChatGPT](templates/17-chatgpt-clipper.json)

### Email and Communication

- [Google Mail](templates/18-google-mail-clipper.json)
- [Outlook Mail](templates/19-outlook-mail-clipper.json)

### GitHub

- [GitHub Issue](templates/20-github-issue-clipper.json)
- [GitHub Pull Request](templates/21-github-pull-request-clipper.json)
- [Github Releases](templates/22-github-releases-clipper.json)
- [GitHub Repository](templates/23-github-repository-clipper.json)

## Requirements

- Obsidian
- Obsidian Web Clipper

## Quick Start

1. Clone or download this repository.
2. Open Obsidian Web Clipper settings in your browser.
3. Import one or more JSON templates from the templates folder.
4. Clip a matching page and confirm the note is created in the expected vault path.
5. Adjust fields such as path, tags, and note name format to match your vault conventions.

## How Templates Work

Most templates include these core fields:

- schemaVersion: Template schema version.
- name: Display name shown in the clipper.
- behavior: Usually create.
- noteContentFormat: Body content and markdown layout.
- properties: Frontmatter-style metadata fields.
- triggers: URL patterns that auto-select a template.
- noteNameFormat: Generated note filename.
- path: Destination folder in your vault.

Templates use placeholder expressions in double braces to extract data from the page and metadata.

## Customization Tips

- Keep noteNameFormat stable and readable to avoid duplicates.
- Start with broad tags in the template, then refine in-note.
- Use URL triggers for high-volume sources (for example GitHub or YouTube).
- If you use AI prompts in noteContentFormat, keep them short and task-specific.
- Test one live clip after every template change.

## Contributing

Contributions are welcome.

1. Add or update template files in the templates folder.
2. Keep naming consistent with existing files.
3. Open a pull request with a clear example use case.

## License

MIT. See LICENSE for details.
