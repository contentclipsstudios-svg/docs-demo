# The complete guide

## Why docs rot

Documentation fails for three reasons: it lives outside the repo, nothing rebuilds it, and nobody owns it. Our pipeline fixes all three — **docs live in the repo, CI rebuilds on every merge, ownership is explicit.**

## The four deliverables

1. **The quickstart** — the 5-minute path from zero to first success. Front page, always.
2. **The guides** — task-oriented, one task per page, no walls of text.
3. **The reference** — auto-generated from OpenAPI, searchable, never stale.
4. **The meta** — changelog, FAQ, contributing. The trust layer.

## The quality bar

Every build passes: link checker, mobile nav, dark mode contrast, sitemap validity, `llms.txt` for AI crawlers.

!!! success "The test"
    A new developer joins your team. They go from clone to first commit **without asking anyone a question**. That's what good docs do.
