# Chalmers beamer theme

A LaTeX beamer theme aiming to be consistent with the [chalmers design manual](https://www.chalmers.se/SiteCollectionDocuments/om%20chalmers%20dokument/Grafisk%20profil/Chalmers%20Design%20Manual%201.0_eng.pdf).

**This is work in progress.**

## Installation

Copy the folder containing the repository to the `tex/latex/` subtree of your
`texmf` folder. On unix systems this usually boils down to the following:

```
cp -r chalmers_beamer_theme ~/texmf/tex/latex/
```

## Usage

After installation, the package can be used by simply calling the `\usetheme` command:

```
\documentclass[presentation]{beamer}
...
\usetheme{chalmers}
...
```
