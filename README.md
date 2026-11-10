# Landmark Studio

Landmark Studio is a browser app for digitizing landmarks and semilandmarks on photographs, for geometric morphometrics. It is a single HTML file: it needs no installation, no server and no internet connection, and it reads and writes TPS files compatible with tpsDig2, geomorph and MorphoJ.

**Use it online:** https://oscarsanisidro.web.uah.es/Investigacion/landmark-studio.html
**DOI:** [10.5281/zenodo.23965715](https://doi.org/10.5281/zenodo.23965715)  
**Use it offline:** download `index.html` and open it in Edge or Chrome.

*Versión en español más abajo.*

## Features

- **Landmarks:** place, move and rename them, mark them as missing (NA), and import their names from a .txt or Word file.
- **Semilandmark curves:** draw a curve from one landmark to another, with its own number of semilandmarks. Smoothing is optional, and the original trace is always kept. A whole curve can be marked NA in a specimen.
- **Scale:** mark it with a ruler, copy it to other specimens, or import the scales of every specimen from a CSV file (name, mm per pixel).
- **Outlines and lines:** draw outlines and straight lines between landmarks for plots. They can be exported as CSV, as TPS, as MorphoJ wireframes or as geomorph links.
- **Review:** finds duplicate IDs, photos without a scale, missing landmarks and mirrored images. The specimen list shows the status of each specimen, with the reason on hover.
- **Languages:** English, Spanish and Chinese.

## Files

| File | What it is |
|---|---|
| `.lmproj` | The working project, written only when you save. |
| `.tps` | Export for geomorph, MorphoJ or tpsRelw. It can also be imported (*File ▸ Import TPS*). |
| `.csv` / `.txt` | Outlines, lines, curveslide tables and scales. |

## Browsers

Edge and Chrome can save straight into the file you choose. Safari and Firefox work in a limited mode, where saving downloads the file.

## How to cite

If you use Landmark Studio in published work, please cite it:

> Sanisidro, O. (2026). *Landmark Studio* (Version 1.0.0) [Computer software]. Zenodo. https://doi.org/10.5281/zenodo.23965715

There are two other ways to get the citation:

- the **Cite this repository** button on this page, which reads `CITATION.cff` and gives APA or BibTeX;
- the **How to cite** button inside the app.

## Credits

Landmark Studio was made by Oscar Sanisidro. It includes [UTIF.js](https://github.com/photopea/UTIF.js) (MIT) for reading TIFF images and [pako](https://github.com/nodeca/pako) (MIT/Zlib).

## License

Landmark Studio is free software: you can redistribute it and/or modify it under the terms of the **GNU General Public License, version 3 or later** ([LICENSE](LICENSE)). Modified versions that are distributed must also be released under the GPL, with their source code.

---

## En español

Landmark Studio es una aplicación de navegador para digitalizar landmarks y semilandmarks sobre fotografías, para morfometría geométrica. Es un único archivo HTML: no necesita instalación, ni servidor, ni conexión a internet, y lee y escribe archivos TPS compatibles con tpsDig2, geomorph y MorphoJ.

**Úsala en línea:** https://oscarsanisidro.github.io/landmark-studio/  
**DOI:** [10.5281/zenodo.23965715](https://doi.org/10.5281/zenodo.23965715)  
**Úsala sin conexión:** descarga `index.html` y ábrelo en Edge o Chrome.

**Qué hace:**

- Coloca landmarks y marca los ausentes (NA).
- Dibuja curvas de semilandmarks entre landmarks, que también pueden marcarse NA.
- Gestiona la escala: con una regla, copiándola a otros especímenes o importándola de un CSV.
- Dibuja contornos y líneas.
- Revisa errores.
- Exporta a TPS.

El proyecto (`.lmproj`) solo se escribe cuando guardas.

**Cómo citar:** usa la referencia de arriba, el botón **Cite this repository** de esta página o el botón **Cómo citar** de la app.

**Licencia:** GNU GPL v3 o posterior. Cualquiera puede usar y modificar la app, pero las versiones modificadas que se distribuyan deben seguir siendo abiertas y con la misma licencia.
