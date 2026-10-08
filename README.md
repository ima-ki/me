# me
dwork  project try 

## Deployment

This is a static HTML/CSS/JavaScript site with no dependencies or compilation step.
The deployable page is `public/index.html`, extracted from `ANGLIKA_v27.zip`
without changing its content. Make future site changes in `public/index.html`.

`netlify.toml` sets the publish directory to `public` and uses `true` as a
successful no-op command to override the invalid `build me` command in Netlify's
UI. No `npm run build` command is needed. Only the site files in `public` are
published, not the repository's archive or documentation.
