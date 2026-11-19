# EV-PRAC-01 — Evaluación de la Unidad I

**Estudiante:** Mendoza Palma Allan Jeremy  
**Asignatura:** Ingeniería de Requerimientos (ISR-401)  
**Nivel y paralelo:** 4.º nivel, paralelo B  
**Período académico:** SPA 2026–2027  
**Fecha:** 18/11/2026  
**Caso:** ALERTARÍO — Sistema de Alerta Temprana de Crecidas

## Archivos

```text
EV-PRAC-01/
├── README.md
├── main.tex
├── main.pdf
├── logoband.png
└── evidencias/
    ├── hoja-01.jpg
    ├── hoja-02.jpg
    └── ...
```

`main.tex` contiene la transcripción de la prueba escrita; `main.pdf` es el documento compilado. Las imágenes de `evidencias/` corresponden a las hojas manuscritas de la evaluación.

## Compilación

- **Compilador:** pdfLaTeX (TeX Live o MiKTeX).
- **Archivo principal:** `main.tex`.
- **Directorio de ejecución:** `EV-PRAC-01/`.
- **Dependencias:** `inputenc`, `fontenc`, `helvet`, `geometry`, `graphicx`, `array`, `tabularx`, `longtable`, `pdflscape`, `colortbl`, `xcolor`, `enumitem`, `fancyhdr`, `lastpage`, `tcolorbox`, `amsmath`, `natbib`, `url`, `needspace`, `caption` y `hyperref`.

Desde la carpeta `EV-PRAC-01/`, ejecutar en este orden:

```bash
pdflatex -interaction=nonstopmode -halt-on-error main.tex
bibtex main
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```
