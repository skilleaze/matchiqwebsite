MATCHIQ COMING SOON — DEPLOY

1. Create a new GitHub repo, e.g. "matchiq".
2. In GitHub Desktop: File > Clone repository > matchiq. Copy all files in this folder into it.
3. Commit "Matchiq coming soon" > Push origin.
4. Vercel > Add New > Project > import "matchiq" > Deploy (no build settings needed).
5. Vercel project > Settings > Domains > add matchiq.skilleaze.com.
   Vercel shows a CNAME record (usually cname.vercel-dns.com). Add it at your domain provider:
   Type CNAME · Name matchiq · Value cname.vercel-dns.com
6. Wait 5–30 min, then open https://matchiq.skilleaze.com

Terminal alternative (inside the folder):
  git init && git add . && git commit -m "Matchiq coming soon"
  git branch -M main
  git remote add origin https://github.com/skilleaze/matchiq.git
  git push -u origin main

AFTER GOING LIVE
- Google Search Console: add property https://matchiq.skilleaze.com, submit sitemap.xml.
- Test the share card: https://www.opengraph.xyz/ (paste the URL) and LinkedIn Post Inspector.
