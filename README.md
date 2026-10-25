# Lami Kamson portfolio

- `index.html`: the site. It reads everything from `content/site.json`.
- `content/site.json`: all your text, numbers and photo paths.
- `admin/`: the editing screen (Sveltia CMS) at `/admin`.
- `api/` and `vercel.json`: the small GitHub login for the editing screen.
- `images/uploads/`: photos you upload in the editor land here.

Never put your GitHub client secret in any file. It goes in Vercel environment variables only.
