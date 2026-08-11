# Codex prompt — maintain ITSBAD Labs site v1

You are working in the GitHub repository `brandinealnku/itsbadlabs`.

Use the existing repository as the source of truth for the production ITSBAD Labs corporate site. Before editing, read `BRAND.md`, `DESIGN.md`, and `AGENTS.md`.

Required outcomes:
- Keep the implementation static HTML/CSS/JS; do not introduce React, Next.js, a build framework, or a CMS unless the architecture is intentionally changed later.
- Preserve the ITSBAD Labs v1 visual system: deep navy `#07111F`, signature pink `#FF66C4`, Inter/system typography, typography-led layout, restrained motion, product-specific accents.
- Preserve all routes: `/`, `/products/`, `/products/recallcheck/`, `/products/knowledge/`, `/labs/`, `/work/`, `/about/`, `/contact/`, `/privacy/`, `/terms/`, `/accessibility/`.
- Keep the v1 wordmark text-based; do not invent a final logo symbol.
- Keep privacy and terms clearly marked as launch placeholders until legal review.
- Do not add fake customers, metrics, testimonials, claims, freshness, or product statuses.
- Verify relative links, asset loading, keyboard focus, mobile menu, and responsive layout at 360, 390, 768, and 1280 px.
- Ensure `wrangler.jsonc` remains suitable for Cloudflare Workers + Static Assets and do not add secrets.

After changes, report:
1. Files added/changed.
2. Validation performed.
3. Any Cloudflare deployment settings that require manual configuration.
4. Any remaining launch blockers.
