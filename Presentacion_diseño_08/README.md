# Presentación de tesis · Consideraciones éticas

**Seminario de Investigación II · Magíster en Psicología Educacional · Universidad de Chile**

Versión derivada de `Presentacion_Tesis_Ajuste_Hipotesis.zip`, con un cambio puntual en la diapositiva 22, sin alterar el documento científico definitivo ni las restantes diapositivas.

## Cambio realizado

Se renombró la diapositiva 22 a **«Consideraciones éticas»**. Ahora presenta únicamente tres componentes: uso de microdatos públicos de PISA 2022; protección de participantes sin reclutamiento directo ni intentos de reidentificación; y comunicación responsable mediante resultados agregados y no estigmatización de escuelas y sistemas educativos. Se eliminaron la ilustración y los textos de planificación, incluida la Carta Gantt, sin moverlos a otra lámina. También se actualizaron las notas orales y el tiempo previsto a **0:35**.

La presentación conserva 23 diapositivas principales, seis anexos, 29 bloques de notas y la identidad visual Academic Navy. El tiempo total planificado pasa de **20:00 a 19:35**, todavía no comprobado mediante ensayo oral. No se modificó el tiempo de otras láminas.

## Archivos

- `presentacion_tesis.qmd`: fuente editable Quarto + RevealJS.
- `styles.css`: estilos, con distribución específica para los tres componentes éticos.
- `assets/`: diagramas SVG referenciados por la presentación (sin la antigua figura de planificación).
- `presentacion_tesis.html`: HTML autónomo, con ilustraciones SVG incorporadas.
- `presentacion_tesis.pdf`: exportación de las 29 diapositivas.
- `manifest.json`: índice y tiempos de cada lámina.
- `Informe_Ajuste_Etica.md`: documentación y auditoría puntual.

## Abrir y presentar

Abrir `presentacion_tesis.html` en un navegador web; usar las flechas para navegar. La tecla **N** abre o cierra las notas de exposición (no aparecen en la diapositiva visible).

## Compilar el QMD con Quarto instalado

```bash
quarto render presentacion_tesis.qmd --to revealjs
```

**Limitación:** Quarto no está instalado en este entorno. Por tanto, el HTML autónomo no debe confundirse con un render oficial de RevealJS; el QMD deberá compilarse en un equipo con Quarto. El PDF se exportó desde el HTML autónomo y fue verificado mediante navegador. La estructura, el contenido y los estilos editables se conservan.

**Consideración sobre la pauta:** al retirar el cronograma, la presentación oral deja de cubrir el criterio de Carta Gantt. Este cambio fue solicitado expresamente y no afecta al Word definitivo.


## Actualización: ecuación combinada del Anexo A

La diapositiva 24 ahora muestra la ecuación combinada completa del modelo M5, derivada de sustituir las ecuaciones de nivel 2 en el modelo de nivel 1. Se mantienen ambas especificaciones por niveles, la varianza residual de pendiente τ11 y el carácter asociativo del análisis. Los otros 28 contenidos de diapositiva permanecen sin cambios.

En el HTML autónomo, abre el anexo con las flechas del teclado; pulsa N para mostrar u ocultar las notas, que explican el significado de los términos.
