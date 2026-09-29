# Qma — developer website

Static pages for Google Play, served by GitHub Pages. No scripts, trackers or external fonts.

| File | Purpose |
|---|---|
| `index.html` | Developer website (the "Website" field in Play Console) |
| `balloon-pop/privacy-policy.html` | Privacy policy of "Pop the balloon!" (`com.babygames.balloonpop`) |
| `app-ads.txt` | AdMob authorized sellers. It is only checked at the domain root: `https://<owner>.github.io/app-ads.txt` |
| `.nojekyll` | Serve files as they are, without Jekyll |

The source of the policy text is `docs/privacy-policy.html` in the game repository. When the text
changes, update both copies and the effective date. Never delete or move a policy page while the
app is on Google Play.
