# Sanidhya Gupta - Academic Portfolio

This repository contains the source code for my personal academic website, hosted on GitHub Pages. 

🌐 **Live Website:** [san-g-8055.github.io/sanidhya-gupta/](https://san-g-8055.github.io/sanidhya-gupta/)

## About Me
I am a Ph.D. student in Computer Science at **Durham University**, working at the intersection of Quantum Information and Networking. My research focuses on modular fault-tolerant quantum computing, distributed quantum error correction, and quantum networking.

## Built With
This website is built using a static site generator and deployed automatically via GitHub Actions.
* **Framework:** [Jekyll](https://jekyllrb.com/)
* **Theme:** [al-folio](https://github.com/alshedivat/al-folio) (A beautiful, clean Jekyll theme for academics)
* **Hosting:** GitHub Pages

## Local Preview
For local preview, use:

```bash
bundle exec jekyll clean
bundle exec jekyll serve --config _config.yml,_config_local.yml
```

Then open:

```text
http://127.0.0.1:4000/
```

The file `_config_local.yml` overrides the GitHub Pages project `baseurl` so styles and images load correctly during local preview.

## License
The theme `al-folio` is open-sourced under the MIT License. The personal content, publications, and images belong to Sanidhya Gupta (© 2026).
