# MONOLITHIC Website Build

This repo holds the code for monolithic.marketing pages and the files that get pasted into GoHighLevel (GHL). Nothing here deploys on its own.

Workflow: edit the code here, the owner reviews the pull request, then the code is pasted into GHL by hand.

## Layout

- `pages/<slug>/` — one folder per page. The HTML file (styles and scripts included) is what gets pasted into that page's custom code in GHL. `notes.md` records the GHL SEO settings: title, description, keywords, slug, and canonical URL.
- `root-files/` — files served at the site root, such as `llms.txt`.
