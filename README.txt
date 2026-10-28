WLX driver safety leaderboard (standalone site)

Files
  index.html  the page drivers open (do not edit for weekly updates)
  data.json   the scores. Replace this one file each time scores are refreshed.

Weekly refresh
  1. Ask Claude to pull the latest scores from Motive and produce a new data.json.
  2. Upload it to your host, replacing the old data.json.

Hosting (free)
  Any static host works (for example GitHub Pages, Netlify or Cloudflare Pages).
  Upload both files to the same place. Check the host's own current instructions
  for uploading; these steps were not tested here.

Notes
  - This page has no login. Anyone with the link can see it.
  - data.json currently holds SAMPLE data (sample: true). Real data sets sample to false.
  - To change how the score is calculated, edit the "weights" in data.json.
