<p align="center">
  <a href="https://legall.tech"><img src="https://legall.tech/img/oss117-issou.png" alt="LeGall"></a>
</p>
<p align="center">
    <em>My personal website</em>
</p>
<p align="center">
<a href="https://app.netlify.com/sites/affectionate-hodgkin-a82a74/deploys" target="_blank">
    <img src="https://api.netlify.com/api/v1/badges/d9de9519-4c11-44c0-a492-86b2a2dce3a0/deploy-status" alt="Netlify Status">
</a>
<a href="https://github.com/JeremyLG/legall.tech/actions" target="_blank">
    <img src="https://github.com/JeremyLG/legall.tech/workflows/Build%20Docs/badge.svg" alt="GitHub Actions Status">
</a>
</p>

---

**Website**: <a href="https://legall.tech" target="_blank">https://legall.tech</a>

**Source Code**: <a href="https://github.com/JeremyLG/legall.tech" target="_blank">https://github.com/JeremyLG/legall.tech</a>

---

My personal website based on the Python library **mkdocs**, GitHub Actions and Netlify.

## Technical Stack
* Python 3.9
    * Poetry for project management
    * MkDocs for website generation
* GitHub Actions
* Netlify

## Project layout
    .github         # The actions and workflows directory
    docs/
        index.md    # The documentation homepage.
        ...         # Other markdown pages, images and other files.
    scripts         # The additional scripts directory.
    .gitignore      # The files and directories to be ignored by Git
    mkdocs.yml      # The MkDocs configuration file.
    poetry.lock     # The automatically generated lock file from Poetry config.
    pyproject.toml  # The Poetry configuration file of the global project.
    README.md       # The project description file.