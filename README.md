## README

**ONDA Lab manual** is the official manual of the organization and philosophy of ONDA Lab (IRCCS San Camillo of Venice).

**[Download the latest version (PDF)](https://github.com/SanCamilloIRCCS-OndaLab/ONDALab-manual/releases/latest/download/ONDA_Lab_Manual.pdf)** · [All versions](https://github.com/SanCamilloIRCCS-OndaLab/ONDALab-manual/releases)

[Lab site](https://sancamilloirccs-ondalab.github.io/)

### Releasing a new version

The PDF is not tracked in git; each version is published as a GitHub release.

1. Bump `version X.Y` on the title page of `ONDA_Lab_Manual.tex` and rebuild (`latexmk -pdf ONDA_Lab_Manual.tex`).
2. Commit and push.
3. `gh release create vX.Y ONDA_Lab_Manual.pdf --title "ONDA Lab Manual vX.Y" --notes "<what changed>"`

The download link above (and the one on the Lab site) always points to the latest release, so the site does not need to change.

## License

This work is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) (Attribution - NonCommercial - ShareAlike). See [LICENSE](LICENSE).
