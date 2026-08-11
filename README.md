# ITSBAD Labs Website

Responsive v1 corporate site for `itsbadlabs.com`.

## Stack
- Static HTML/CSS/JS
- Cloudflare Workers + Static Assets
- ITSBAD Labs Design System v1.0

## Local preview
Run a static web server from the repository root, e.g. `python3 -m http.server 8000`.

## Cloudflare
Connect this repository to Cloudflare Workers Builds. The included `wrangler.jsonc` defines the repository root as the static asset directory. For a Git-connected dashboard deployment, use the Worker/Static Assets defaults appropriate to the Cloudflare UI and verify the build before attaching `itsbadlabs.com`.

Git-backed production deployment enabled August 11, 2026.

## Notes before public launch
- Replace Privacy and Terms placeholders with reviewed final language.
- Connect a dedicated ITSBAD Labs business email/contact workflow.
- Update RecallCheck and Knowledge production URLs after branded subdomains are attached.
- Add final proprietary compact logo mark when approved; the wordmark is canonical for v1.

© 2026 ITSBAD LLC. All rights reserved.
