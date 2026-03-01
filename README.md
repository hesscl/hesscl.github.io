# hesscl.github.io

Personal academic website for [Chris Hess](https://hesscl.com), Assistant Professor of Sociology at Kansas State University.

Built with [al-folio](https://github.com/alshedivat/al-folio) and hosted on GitHub Pages at **[hesscl.com](https://hesscl.com)**.

## Structure

| Path | Contents |
|---|---|
| `_config.yml` | Site-wide configuration |
| `_pages/` | About, Publications, Software, CV, Teaching, 404 |
| `_bibliography/papers.bib` | Full publications bibliography |
| `_data/cv.yml` | CV data (Education, Experience, Awards) |
| `_projects/` | Software project pages |
| `assets/img/prof_pic.jpg` | Profile photo |
| `CNAME` | Custom domain (hesscl.com) |
| `.github/workflows/deploy.yml` | GitHub Actions build → gh-pages |

## Local Development

Requires Ruby, Bundler, and Jekyll.

```bash
bundle install
bundle exec jekyll serve
```

Site is served at `localhost:4000`.

## Deployment

Pushes to `master` trigger a GitHub Actions workflow that builds the site and pushes the result to the `gh-pages` branch. GitHub Pages serves from `gh-pages`.
