# Blue Ember Reiki Academy · App design demo

`index.html` switches between two self-contained prototypes, `student.html` and `instructor.html`. Sample data only, no logins or real records. Keep all five files (`index.html`, `student.html`, `instructor.html`, `logo-shield.png`, `Staticfile`) together.

## Publish on GitHub + Railway

1. Create a new GitHub repo (e.g. `blue-ember-academy-demo`) and add all files from this folder to its root.
2. In Railway: **New Project → Deploy from GitHub repo** → pick the repo. Railway detects `Staticfile` and serves the folder as a static site.
3. In the service's **Settings → Networking**, click **Generate Domain** for a public `*.up.railway.app` link, or add a custom domain (e.g. `academy.blueemberwellnessrva.com`) and set the CNAME it gives you at your DNS host.

To update the demo, replace the files in the repo and push; Railway redeploys automatically.
