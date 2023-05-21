# Hugo Webring

A webring built on top of [Hugo](https://gohugo.io/) and [Openring](https://github.com/wheresalice/openring)

Inspired by [webring-starter](https://github.com/krusynth/webring-starter)

## Configuration

1. Set your site name and URL in `config/_default/config.yml`, `config/_default/params.yml` and `static/webring.js`
2. Edit your sites in `static/sites.json`
3. Edit your site's hostname in `.github/workflows/gh-pages.yml`
4. Configure GitHub pages to publish from the gh-pages branch
5. Uncomment the scheduled rebuilds of rss content from `.github/workflows/gh-pages.yml`

## Tools Used

- Alice's fork of [Openring](https://github.com/wheresalice/openring)
- [hugo-theme-readable](https://github.com/cjtheham/hugo-theme-readable)
- GitHub Actions
- GitHub Pages
- Hugo
