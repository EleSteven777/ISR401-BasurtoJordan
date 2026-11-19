# ISR401-BasurtoJordan
Repositorio personal de Ingeniería de Requerimientos (ISR-401), UTEQ.

## Contenido
- `FORM-TL-01/`: taller de tipos de requisitos (plataforma de gestión de citas médicas).
  - `main.tex`: fuente del documento en LaTeX.
  - `main.pdf`: PDF compilado.
- `TA-IND-01/`: trabajo individual sobre IEEE 29148 y tipos de requisitos de un sistema conocido (Epic Games Store).
  - `main.tex`: fuente del informe en LaTeX.
  - `referencias.bib`: referencias en estilo IEEE.
  - `figuras/`: capturas propias del sistema.
  - `main.pdf`: PDF compilado.
 
## Cómo compilar TA-IND-01
- Archivo principal: `TA-IND-01/main.tex` (referencias en `TA-IND-01/referencias.bib`, capturas en `TA-IND-01/figuras/`)
- Compilador: pdfLaTeX con BibTeX (TeX Live, el predeterminado de Overleaf)
- Comandos, en orden (dentro de `TA-IND-01`):
  1. `pdflatex main.tex`
  2. `bibtex main`
  3. `pdflatex main.tex`
  4. `pdflatex main.tex`
- Dependencias (paquetes LaTeX): inputenc, fontenc, babel (spanish), geometry, graphicx, longtable, array, xcolor (table), fancyhdr, hyperref, caption, pdflscape, enumitem, IEEEtran (estilo bibliográfico)

## Cómo compilar EV-PRAC-01

Transcripción fiel de la evaluación escrita a mano el 18-11-2026 (caso FRÍOVAC).

- Carpeta: `EV-PRAC-01/`
- Archivo principal: `EV-PRAC-01/main.tex`
- Compilador: pdfLaTeX (en Overleaf, menú Compiler → pdfLaTeX)
- Orden de comandos: `pdflatex main.tex` (ejecutarlo dos veces)
- Paquetes: babel (spanish), geometry, array, longtable, graphicx, enumitem
- Las fotografías de las hojas están en `EV-PRAC-01/evidencias/` (hoja-01.jpg, hoja-02.jpg, hoja-03.jpg) y se incluyen en el anexo del PDF.

