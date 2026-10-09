# allonsy-studio.github.io

Org-level GitHub Pages site for `projects.allons-y.studio`. Every repository in the `allonsy-studio` org that publishes GitHub Pages is served at `projects.allons-y.studio/<repo>`.

The apex URL has no content of its own: it redirects to [allons-y.studio/tools](https://allons-y.studio/tools).

## How it works

- `CNAME` binds the custom domain `projects.allons-y.studio`.
- `index.html` redirects the apex (`/`) to `https://allons-y.studio/tools`.
- `404.html` redirects unknown paths to the same place.

## DNS

Add a `CNAME` record: `projects` → `allonsy-studio.github.io`. Then enable Pages (deploy from `main`, root) and enforce HTTPS in the repo settings.

## License

[MPL-2.0](LICENSE)

---

Made with care by [Allons-y Studio](https://allons-y.studio).
