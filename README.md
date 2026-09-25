# AnthonyHub

A standalone assignment tracker across Shoreline CC (Art, English, Engineering)
and Shorewood AP classes (Calc BC, CS, Physics II).

## Files
- `index.html` — the site
- `data.json` — the assignment list (edit or regenerate to update)

## Deploy to Vercel (about 1 minute)
Option A — drag & drop (no Git):
1. Go to vercel.com, sign in.
2. Add New → Project → deploy from a folder, or use the Vercel CLI:
   `npm i -g vercel` then `vercel` inside this folder, follow prompts.
3. It serves index.html as the site root. Done.

Option B — GitHub → Vercel (auto-redeploys on changes):
1. Put this folder in a GitHub repo.
2. Vercel → Add New → Project → Import that repo → Deploy.
3. To update assignments later, replace data.json and push; Vercel redeploys.

## Notes
- Check-offs and your own to-dos save in the browser (per device).
- To refresh assignments, replace `data.json` with a newer version.
