
# Chaos Sandbox

Chaos Sandbox is a plain static website made with only HTML, CSS, and JavaScript.
It runs directly in a browser and does not need a build step, backend, package manager, or external CDN.

## Pages

- `index.html` - Home page
- `pendulum.html` - Double pendulum simulation
- `lorenz.html` - Lorenz attractor simulation
- `wave.html` - Wave interference simulation
- `bifurcation.html` - Logistic map bifurcation diagram
- `nbody.html` - N-body gravity simulation
- `styles.css` - Shared styling
- `utils.js` - Shared helper code

## Run Locally

Open `index.html` in a browser.

Or run a simple local server from this folder:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```



## Git Commands

If using Git from the command line:

```bash
git init
git add .
git commit -m "Add Chaos Sandbox website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git push -u origin main
```

Replace `YOUR-USERNAME` and `YOUR-REPO-NAME` with your real GitHub username and repository name.
