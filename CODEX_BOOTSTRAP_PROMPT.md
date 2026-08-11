# Codex prompt — publish ITSBAD Labs site v1

You are working in the GitHub repository `itsbadlabs/itsbadlabs-site`.

Build the initial production-ready corporate site for ITSBAD Labs using the supplied repository package as the source of truth. Preserve the exact folder structure and contents from the package. Before editing, read `BRAND.md`, `DESIGN.md`, and `AGENTS.md`.

Required outcomes:
- Add all supplied files to the repository.
- Keep the implementation static HTML/CSS/JS; do not introduce React, Next.js, a build framework, or a CMS.
- Preserve the ITSBAD Labs v1 visual system: deep navy `#07111F`, signature pink `#FF66C4`, Inter/system typography, typography-led layout, restrained motion, product-specific accents.
- Preserve all routes: `/`, `/products/`, `/products/recallcheck/`, `/products/knowledge/`, `/labs/`, `/work/`, `/about/`, `/contact/`, `/privacy/`, `/terms/`, `/accessibility/`.
- Keep the v1 wordmark text-based; do not invent a final logo symbol.
- Keep privacy and terms clearly marked as launch placeholders until legal review.
- Do not add fake customers, metrics, testimonials, claims, or product statuses.
- Verify relative links, asset loading, keyboard focus, mobile menu, and responsive layout at 360, 390, 768, and 1280 px.
- Ensure `wrangler.jsonc` remains suitable for Cloudflare Workers + Static Assets and do not add secrets.
- Commit the work in one focused branch/PR titled `Build ITSBAD Labs v1 site`.

After implementation, report:
1. Files added/changed.
2. Local validation performed.
3. Any Cloudflare deployment settings I must configure manually.
4. Any remaining launch blockers.
