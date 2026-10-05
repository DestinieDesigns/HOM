# House of Mercy AI Social Media Companion

Complete static GitHub Pages app for ACCI House of Mercy.

Pages: Companion, Talk, Learn, Data, Church.

This version works without an API key. Talk uses a local assistant so the site is immediately usable. CSV data and church knowledge are stored locally in the browser. No permanent photo/video library is included.

Deploy by placing these files in the repository root and enabling GitHub Pages from `main` / root.

For a production AI model, replace the local `reply()` function with a server-side AI endpoint. Never expose a private API key in browser JavaScript.
