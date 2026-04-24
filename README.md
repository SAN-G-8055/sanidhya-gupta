# Sanidhya Gupta Academic Website

This repository contains a GitHub Pages-ready academic website built with the `al-folio` Jekyll theme structure and conventions. The design is intentionally minimal, white-and-blue, and optimized for a research-focused academic profile.

## Project structure

```text
sanidhya-gupta-academic-site/
├── .github/
│   └── workflows/
│       └── pages.yml
├── _bibliography/
│   └── papers.bib
├── _data/
│   └── cv.yml
├── _news/
│   ├── 2025-10-01-phd-start.md
│   └── 2026-01-15-research-update-placeholder.md
├── _pages/
│   ├── about.md
│   ├── contact.md
│   ├── cv.md
│   ├── publications.md
│   ├── research.md
│   └── talks.md
├── _sass/
│   └── _custom.scss
├── assets/
│   ├── css/
│   │   └── main.scss
│   ├── img/
│   │   ├── favicon.svg
│   │   └── profile-placeholder.svg
│   └── pdf/
│       └── Sanidhya_Gupta_CV.pdf
├── index.md
├── Gemfile
└── _config.yml
```

## Placeholders you should replace

Update the following before deployment:

1. GitHub username and repository name
   - File: [`_config.yml`](/Users/sqgh94@durham.ac.uk/Downloads/sanidhya-gupta-academic-site/_config.yml)
   - Replace:
     - `REPLACE_WITH_GITHUB_USERNAME`
   - Repository name is set to `sanidhya-gupta`

2. Google Scholar profile
   - File: [`_config.yml`](/Users/sqgh94@durham.ac.uk/Downloads/sanidhya-gupta-academic-site/_config.yml)
   - Replace:
     - `REPLACE_WITH_SCHOLAR_ID`
     - `REPLACE_WITH_SCHOLAR_URL` in the content pages if you prefer a full custom URL

3. LinkedIn profile
   - File: [`_config.yml`](/Users/sqgh94@durham.ac.uk/Downloads/sanidhya-gupta-academic-site/_config.yml)
   - Replace:
     - `REPLACE_WITH_LINKEDIN_USERNAME`

4. Profile image
   - Current placeholder: [`assets/img/profile-placeholder.svg`](/Users/sqgh94@durham.ac.uk/Downloads/sanidhya-gupta-academic-site/assets/img/profile-placeholder.svg)
   - Recommended replacement path: `assets/img/profile.jpg`
   - If you rename the file, update the image path in [`index.md`](/Users/sqgh94@durham.ac.uk/Downloads/sanidhya-gupta-academic-site/index.md)

5. CV PDF
   - Current placeholder file: [`assets/pdf/Sanidhya_Gupta_CV.pdf`](/Users/sqgh94@durham.ac.uk/Downloads/sanidhya-gupta-academic-site/assets/pdf/Sanidhya_Gupta_CV.pdf)
   - Replace it with your actual CV PDF using the same filename, or update the links in:
     - [`index.md`](/Users/sqgh94@durham.ac.uk/Downloads/sanidhya-gupta-academic-site/index.md)
     - [`_pages/cv.md`](/Users/sqgh94@durham.ac.uk/Downloads/sanidhya-gupta-academic-site/_pages/cv.md)

6. Favicon
   - Current placeholder: [`assets/img/favicon.svg`](/Users/sqgh94@durham.ac.uk/Downloads/sanidhya-gupta-academic-site/assets/img/favicon.svg)
   - Replace with your preferred icon asset and update references if needed

## Content maintenance

The site is organized so routine updates stay simple:

- Publications: edit [`_bibliography/papers.bib`](/Users/sqgh94@durham.ac.uk/Downloads/sanidhya-gupta-academic-site/_bibliography/papers.bib)
- Talks and presentations: edit [`_pages/talks.md`](/Users/sqgh94@durham.ac.uk/Downloads/sanidhya-gupta-academic-site/_pages/talks.md)
- CV entries: edit [`_data/cv.yml`](/Users/sqgh94@durham.ac.uk/Downloads/sanidhya-gupta-academic-site/_data/cv.yml)
- Research themes: edit [`_pages/research.md`](/Users/sqgh94@durham.ac.uk/Downloads/sanidhya-gupta-academic-site/_pages/research.md)
- News items: add Markdown files to [`_news/`](/Users/sqgh94@durham.ac.uk/Downloads/sanidhya-gupta-academic-site/_news)

## Local preview

Make sure Ruby and Bundler are installed, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open the local preview URL shown in the terminal, usually `http://127.0.0.1:4000`.

## GitHub Pages deployment

This repository includes a GitHub Actions workflow at [`.github/workflows/pages.yml`](/Users/sqgh94@durham.ac.uk/Downloads/sanidhya-gupta-academic-site/.github/workflows/pages.yml) so you can deploy with custom Jekyll plugins such as `jekyll-scholar`.

### Recommended steps

1. Create a GitHub repository.
2. Push this project to the repository.
3. In GitHub, open `Settings` -> `Pages`.
4. Under `Build and deployment`, choose `GitHub Actions`.
5. Commit and push your changes to the default branch.
6. GitHub Actions will build and publish the site automatically.

### For a user site

Use a repository named:

```text
YOUR_GITHUB_USERNAME.github.io
```

Then keep:

```yaml
baseurl: ""
```

### For a project site

This project is currently configured for a repository named `sanidhya-gupta`. Update:

```yaml
url: "https://YOUR_GITHUB_USERNAME.github.io"
baseurl: "/sanidhya-gupta"
repository: YOUR_GITHUB_USERNAME/sanidhya-gupta
```

## Notes

- The site uses `al-folio` conventions while keeping content in Markdown, YAML, and BibTeX for easy maintenance.
- The home page and footer include clearly marked placeholders rather than invented information.
- The publications page is designed to render from BibTeX via `jekyll-scholar`, which is why GitHub Actions deployment is included.
