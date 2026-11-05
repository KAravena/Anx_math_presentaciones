# Presentación de tesis · H3 fundamentada con logo FACSO · 21 diapositivas

Versión final con el imagotipo oficial de **Facultad de Ciencias Sociales, Universidad de Chile** en la esquina superior derecha de la portada, sustituyendo las tres líneas institucionales anteriores. Se conservan la fundamentación oral de H3 en las notas 7 y 9 y la contribución a Psicología Educacional desde América Latina y el Caribe en la última diapositiva.

## Archivos principales

- `Presentacion_Tesis_21_H3_FACSO_Final.html`: presentación HTML autónoma (logo incluido dentro del archivo); abrir en navegador. Las notas se muestran con `N` o el control Notas.
- `Presentacion_Tesis_21_H3_FACSO_Final.qmd`: fuente Quarto editable; requiere `estilos_tesis.scss`, `assets/` y `referencias.bib`.
- `Presentacion_Tesis_21_H3_FACSO_Final.pdf`: presentación de 21 páginas con la portada actualizada.
- `assets/logo_facso_horizontal.png`: imagen del logo original de FACSO, extraída de un documento académico del usuario, recortada únicamente para eliminar márgenes blancos.
- `GUION_ORAL_21_LAMINAS.md`: guion oral vigente con H3 fundamentada.
- `INFORME_IMPLEMENTACION_LOGO_FACSO.md`: detalles y controles de esta actualización.
- `INFORME_IMPLEMENTACION_H3.md`: trazabilidad de los ajustes previos a la justificación de H3.
- `Portada_Logo_FACSO.png` y `Portada_Logo_FACSO_1920x1080.png`: vistas previas de la portada real del HTML.

## Verificación

- Exactamente 21 diapositivas.
- La única diapositiva visualmente modificada es la **portada**; 2–21 permanecen idénticas píxel a píxel en el PDF.
- El guion oral no fue modificado en esta actualización.
- El HTML autónomo funciona en Chromium y el logo se carga correctamente desde la imagen embebida.
- El compilador Quarto no está disponible aquí; la compilación nativa sigue pendiente.

## Compilación opcional en Quarto

```bash
quarto render Presentacion_Tesis_21_H3_FACSO_Final.qmd --to revealjs
```

El HTML distribuido es una versión autónoma; no se presenta como un render nativo nuevo de Quarto.
