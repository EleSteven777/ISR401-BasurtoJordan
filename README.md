# ISR401-BasurtoJordan
Repositorio personal de Ingeniería de Requerimientos (ISR-401), UTEQ.

## Contenido
- `FORM-TL-01/`: taller de tipos de requisitos (plataforma de gestión de citas médicas).
  - `main.tex`: fuente del documento en LaTeX.
  - `main.pdf`: PDF compilado.

## Cómo compilar FORM-TL-01
- Archivo principal: `FORM-TL-01/main.tex`
- Compilador: pdfLaTeX (el predeterminado de Overleaf, TeX Live)
- Comandos, en orden:
  1. `cd FORM-TL-01`
  2. `pdflatex main.tex`
  3. `pdflatex main.tex` (segunda pasada para pie de página y referencias)
- Dependencias (paquetes LaTeX): inputenc, fontenc, babel (spanish), geometry, longtable, array, xcolor (table), fancyhdr, hyperref
