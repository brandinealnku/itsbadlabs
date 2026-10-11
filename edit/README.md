# EDIT — Private Style Studio

This is the browser-based EDIT v0.4 application, kept isolated from the ITSBAD Labs main website on the `edit-style-studio` branch.

## Deploy using Cloudflare Pages + Git

1. In Cloudflare choose Workers & Pages > Create > Pages > Connect to Git.
2. Select GitHub repository `brandinealnku/itsbadlabs`.
3. Set the **production branch** to `edit-style-studio` (not `main`).
4. Select the root directory `edit` (where index.html lives), or configure build output directory `edit` if root-directory selection isn't offered.
5. Framework preset: None; no build command. Deploy.
6. Confirm the *.pages.dev preview first. Then add custom domain `edit.itsbadlabs.com`.

## Important limits

- Photos and wardrobe entries use browser-local storage, not a private account, and will not sync across devices or browsers.
- Do not commit wardrobe images, personal data, or API keys to this public repository.
- The optional third-party vision service sends image data off-device when explicitly used. Use only temporary personal API keys; production use requires a backend.
- This is an evaluation build, not a secure production wardrobe service.
