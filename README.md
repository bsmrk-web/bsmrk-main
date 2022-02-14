# www.bismarckanalysis.com

## How to update the website

The website is currently a Vue site, the source code for which is currently just maintained out of https://github.com/csvoss/bismarckanalysis.

To redeploy the website for any given Vue changes, run `make dist` in that repo, then copy the following files over to `docs/` here:

* `dist/index.html` -> `docs/index.html`
* `dist/images/*` -> `docs/images/*`
* `dist/js/*` -> `docs/js/*`
* `dist/css/*` -> `docs/css/*`
* `dist/fonts/*` -> `docs/fonts/*`
