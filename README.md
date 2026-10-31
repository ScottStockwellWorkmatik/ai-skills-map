# Marketing Skills Map

A browser-only page for organisations to rank the top 10 marketing skills for 2027 by strategic priority, rate their team's current coverage of each skill (0 = no one has the skill, 10 = every team member is fully skilled) and see the result on one map. The ranking and map can be downloaded as an Excel workbook. Nothing is sent or stored. Workmatik brand.

Live address (after GitHub Pages is switched on): https://scottstockwellworkmatik.github.io/ai-skills-map/

## Files

```
index.html            The whole page (styles, skills list, app code and the Excel library are inside it)
og-image-1200.png     LinkedIn and social preview image (1200 x 630)
favicon files         favicon.ico, favicon.svg, favicon-96x96.png, apple-touch-icon.png, web-app-manifest-*.png, site.webmanifest
.nojekyll             Tells GitHub Pages to serve the files as they are
```

## Publishing

Upload the contents of the folder (not the folder itself) so `index.html` is at the top of the repository, then switch on GitHub Pages for the main branch.

## Changing the skills

The ten skills are listed near the end of `index.html` in the `SKILLS` list (id, title and short tag). The id is also the default rank.
