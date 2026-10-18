# The 24-hour docs workflow

1. **Framework choice** — Docusaurus (React, versioning, API pages) vs MkDocs Material (fastest theming). Picked by your stack.
2. **Information architecture before content** — versioned docs, guides vs reference split, working search.
3. **Content restructure** — buried Markdown into the sidebar, every relative link fixed (this is where migrations die), quickstart on the front page.
4. **API reference auto-generated** from the OpenAPI spec — never hand-written.
5. **CI/CD on every merge** — docs rebuild like code. Without this, docs rot.
6. **Final checklist** — link checker, mobile nav, dark mode, sitemap + `llms.txt`.

!!! tip "Run it yourself"
    This site was built and deployed with steps 1-6 — nothing hand-wired.
