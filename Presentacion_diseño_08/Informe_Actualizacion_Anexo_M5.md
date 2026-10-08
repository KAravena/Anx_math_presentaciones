# Informe de actualización · Anexo A, modelo M5

## Solicitud atendida
Se añadió al **Anexo A (diapositiva 24)** la **ecuación combinada completa de M5**, sustituyendo las ecuaciones de nivel 2 en la ecuación de nivel 1. Se conserva también la formulación separada por niveles.

## Modelo combinado

\[
\begin{aligned}
Y_{ij}={}&\gamma_{00}+\gamma_{01}Comp_j+\gamma_{10}Ansiedad_{ij}\\
&+\gamma_{11}(Ansiedad_{ij}\times Comp_j)+\gamma_{20}NSE_{ij}\\
&+\gamma_{30}Mujer_{ij}+u_{0j}+u_{1j}Ansiedad_{ij}+e_{ij}.
\end{aligned}
\]

El término de interacción **γ11(Ansiedad × Composición)** está diferenciado en verde petróleo para facilitar su identificación. Se destaca además **Var(u1j) = τ11** y la interpretación observacional.

## Fiel al documento definitivo
Ansiedad y NSE individual están centradas en las medias escolares ponderadas, y composición en la media del sistema. Las notas aclaran que en M5 γ10 es el gradiente para la composición media y τ11 recoge variabilidad residual de pendientes. H1/H2 se evalúan inicialmente en M3; H3 en M5. No se alteró la especificación ni se agregaron predictores.

## Alcance
Cambio exclusivo del Anexo A; 23 diapositivas principales y 6 anexos, sin alterar la duración de la exposición. Quarto debe compilarse en un entorno que lo tenga instalado; el HTML autónomo y el PDF se validan por separado.

## Verificación técnica y visual

- 29 diapositivas en el HTML y 29 páginas en el PDF.
- Comparación del texto del PDF anterior y el actualizado: **solo cambió la página 24** (Anexo A).
- Inspección mediante Chromium a 1600 × 900 de las 29 diapositivas: **sin desbordes de contenido y sin elementos fuera del lienzo**.
- La ecuación combinada, el nivel 1, el nivel 2 y el rótulo de la varianza caben dentro de la diapositiva.
- Se conservan las 29 notas del presentador, la estructura de 23 diapositivas principales + 6 anexos y los 20 minutos de referencia de la versión previa (última duración planificada: 19:35).
- Archivo HTML autónomo y PDF generados; **compilación oficial Quarto no ejecutada** por no estar disponible en el entorno.
