# Spotify Email

This folder keeps both the MJML source and the compiled HTML preview for a Spotify Premium receipt email.

## Live Preview

[Open on GitHub Pages](https://joelmuhoho.github.io/email_dev/spotify_email_live/)

## Files

- `index.mjml`: editable source
- `index.html`: rendered output

## Rebuild

Install MJML if needed, then regenerate the HTML output.

```bash
mjml index.mjml -o index.html
```

## Preview

Open either file in an editor or browser, but make changes in `index.mjml` first.