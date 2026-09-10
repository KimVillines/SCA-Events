Section 39RS Seating Chart — GitHub Pages Setup
1. Create the repo
Go to https://github.com/new
Name it anything (e.g. `seating-chart`)
Set it to Public (GitHub Pages on the free plan requires a public repo)
Click Create repository
2. Upload the file
On your new repo's page, click Add file → Upload files
Drag in `index.html` (the file from this download, renamed to `index.html`)
Click Commit changes
3. Turn on GitHub Pages
In the repo, go to Settings → Pages
Under "Build and deployment," set Source to Deploy from a branch
Set Branch to `main` (or `master`) and folder to `/ (root)`
Click Save
Wait ~1 minute, then refresh — GitHub will show you a URL like:
`https://yourusername.github.io/seating-chart/`
4. Get your real shareable link
Open that URL in your browser
The page will automatically create a shared data slot and update the
address bar to something like:
`https://yourusername.github.io/seating-chart/?chart=abc123XYZ`
A gold banner will appear at the top with that exact link and a
Copy link button
This is the link you share with everyone — not the plain URL from
step 3. The `?chart=...` part is what makes everyone see the same seats.
Notes
No account, signup, or API key needed — it uses jsonblob.com, a free
public JSON storage service, behind the scenes.
If a shared chart isn't opened by anyone for 75 days, jsonblob may clear
it. If that happens, the page falls back to a fresh blank chart, so keep
a backup by clicking Export chart (.json) occasionally if you want
extra safety.
Because this is a public, unauthenticated data store, treat the link like
an unlisted document: anyone who has it can view and edit it, so only
share it with people you want editing the chart.
