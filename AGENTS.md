# AGENTS.md

## Project Overview

tools is a tiny static site that lists Brian's open source CLI tools and links to their hosted pages.
The site lives in docs/ and is deployed to GitHub Pages via Actions.

## Development Commands

```bash
# Serve the site locally
python3 -m http.server --directory docs
```

## Formatting

Run `ffx` to format HTML, CSS, and Markdown before finishing.

## Testing

No automated tests. Verify the page in a browser.
