# Realtors Landing Pages

Static, single-page HTML assets powering a simple marketing funnel for real estate agents.

## Pages
- **overview.html**: Top-of-funnel overview and value proposition
- **your-plan.html**: Personalized plan and next steps
- **book.html**: Booking/scheduling call-to-action
- **bottom_funnel_realtors.html**: Bottom-of-funnel sales page
- **thank-you.html**: Post-conversion confirmation

## Quick start (local preview)
- Node: `npx serve@latest . --listen 8080`
- Python 3: `python -m http.server 8080`

Then visit `http://localhost:8080/overview.html` (or any page above).

## Deployment
- Hosted on Netlify
- `netlify.toml` contains site configuration
- `_redirects` defines redirects/rewrite rules

Typical flow: push to your default branch and Netlify auto-deploys, or drag-and-drop this folder in the Netlify UI to trigger a deploy.

## Project structure
- HTML files and assets live at the repository root for simplicity
- Images and media examples:
  - `oneclick logo orange square.png`, `one click seo new logo.png`
  - `dc-id.jpg`, `heather murphy.jpg`
  - `Dominating_Local_Search.mp4`, `grant-clayton-founder-1percent-lists.mp4`
  - `dominate the map.png`

Add new assets alongside the HTML files and reference them with relative paths.

## Editing guidelines
- Use HTML5 semantics and include responsive meta tags
- Keep internal links relative (e.g., `./book.html`, `./thank-you.html`)
- Optimize media (compress images; MP4 H.264/AAC; keep file sizes reasonable)
- Provide descriptive titles/meta and `alt` text for images
- Test on mobile and desktop

## Redirects and routing
- For pretty URLs or default routes, update `_redirects`
- Example: mapping `/` to `overview.html`

## License and attribution
Ensure you have rights to use all included media. Add attribution or licenses as required by your organization.