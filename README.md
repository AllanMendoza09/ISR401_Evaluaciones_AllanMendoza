# ISR401 — Evaluaciones de Ingeniería de Requerimientos

Repositorio de las evaluaciones de la asignatura **Ingeniería de Requerimientos (ISR-401)** de la Universidad Técnica Estatal de Quevedo (UTEQ). Cada evaluación se organiza en una carpeta independiente con su documento LaTeX, PDF y evidencias correspondientes.

**Estudiante:** Mendoza Palma Allan Jeremy  
**Carrera:** Ingeniería de Software  
**Nivel y paralelo:** 4.º nivel, paralelo B  
**Período académico:** SPA 2026–2027  
**Repositorio:** https://github.com/AllanMendoza09/ISR401_Evaluaciones_AllanMendoza.git

## Evaluaciones

| Código | Evaluación | Caso | Fecha | Carpeta |
|---|---|---|---|---|
| EV-PRAC-01 | Evaluación de la Unidad I: Fundamentos de Ingeniería de Requisitos | ALERTARÍO | 18/11/2026 | [EV-PRAC-01](EV-PRAC-01/) |

## Estructura del repositorio

```text
ISR401_Evaluaciones_AllanMendoza/
├── README.md
└── EV-PRAC-01/
    ├── README.md
    ├── main.tex
    ├── main.pdf
    ├── logoband.png
    └── evidencias/
        ├── hoja-01.jpg
        ├── hoja-02.jpg
        └── ...
```

## Compilación de EV-PRAC-01

- **Compilador:** pdfLaTeX, con BibTeX para las referencias.
- **Distribución:** TeX Live o MiKTeX.
- **Archivo principal:** `EV-PRAC-01/main.tex`.
- **Dependencias LaTeX:** `inputenc`, `fontenc`, `helvet`, `geometry`, `graphicx`, `array`, `tabularx`, `longtable`, `pdflscape`, `colortbl`, `xcolor`, `enumitem`, `fancyhdr`, `lastpage`, `tcolorbox`, `amsmath`, `natbib`, `url`, `needspace`, `caption` y `hyperref`.

Desde la raíz del repositorio, ejecutar:

```bash
cd EV-PRAC-01
pdflatex -interaction=nonstopmode -halt-on-error main.tex
bibtex main
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

Las instrucciones específicas de esta evaluación también se encuentran en [EV-PRAC-01/README.md](EV-PRAC-01/README.md). Al añadir otra evaluación, se incorporará su carpeta al índice y a la estructura general.
