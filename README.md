# ARTES Cloud Desktop releases

Public installer distribution for **ARTES Cloud Desktop**.

## Download

- **Download page (GitHub Pages):** https://brassco-artes.github.io/molainn-desktop-releases/
- **GitHub Releases:** https://github.com/brassco-artes/molainn-desktop-releases/releases

Use the **Assets** installers only (or the download page above). GitHub always lists **Source code (zip|tar.gz)** under every release; with `.gitattributes` `export-ignore` those archives are empty and are **not** the desktop app.

Builds are published from the private source repo via CI. Packaged apps update from the same Releases feed via `electron-updater`.
