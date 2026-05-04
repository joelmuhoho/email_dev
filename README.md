# Email Development Workspace

> [!NOTE]
> This repository is a collection of independent email templates and previews. There is no single top-level build command.

This workspace emails projects in a few formats: standalone HTML previews, MJML source with compiled output. Each folder has its own README with the exact workflow for that project.

## Projects

| Folder | Format | Live | Notes |
| --- | --- | --- | --- |
| [calendly_email_live](calendly_email_live/README.md) | Standalone HTML | [Open](https://joelmuhoho.github.io/email_dev/calendly_email_live/) | Calendly-style workflow email preview. |
| [shopify_email_live](shopify_email_live/README.md) | Standalone HTML | [Open](https://joelmuhoho.github.io/email_dev/shopify_email_live/) | Shopify-branded email preview. |
| [spotify_email_live](spotify_email_live/README.md) | MJML + HTML | [Open](https://joelmuhoho.github.io/email_dev/spotify_email_live/) | MJML source plus compiled receipt email. |
| [watch_email_live](watch_email_live/README.md) | Standalone HTML | [Open](https://joelmuhoho.github.io/email_dev/watch_email_live/) | Smartwatch-themed responsive email preview. |

## Working With The Repo

- Open any `index.html` file directly to preview a finished email.
- If a folder includes `index.mjml`, edit the MJML source and regenerate the HTML output.
- Use the folder-specific instructions in `kayak-email` for build, zip, Litmus, and mail workflows.
- Many templates load images from hosted URLs, so previews may depend on network access.
