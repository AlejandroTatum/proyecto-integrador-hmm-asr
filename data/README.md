# Datos y corpus documental

La APE 007 establece la estructura inicial del proyecto y no requiere todavía una ejecución experimental ni la publicación de conjuntos de datos.

Como insumo documental se dispone de una exportación de Scopus realizada el **20 de mayo de 2026**, con 321 registros relacionados con HMM y reconocimiento de voz. El archivo bruto se conserva como evidencia académica local y no se publica en este repositorio, porque contiene registros y resúmenes que no son citados directamente en el documento.

En etapas posteriores, esta carpeta podrá contener matrices de extracción o datos experimentales autorizados para publicación.

## Fuentes bibliográficas HMM-ASR

La tabla `fuentes_hmm_asr_28.csv` registra las 28 fuentes activas seleccionadas para el corpus HMM-ASR, con DOI, metadatos principales y estado local del PDF. Los PDFs completos no se publican en GitHub por trazabilidad ética y derechos de autor; se conservan únicamente en la biblioteca local de trabajo.

La bibliografía activa del corpus está en `../refs/fuentes_hmm_asr_28.bib`. La bibliografía `../refs/referencias_hmm_asr_curadas.bib` se mantiene como subconjunto de referencias efectivamente citadas en el documento principal.

## Capítulo final de libro

Para la versión final del Capítulo 21 se añadieron dos archivos de trazabilidad:

- `capitulo_21_materiales_usados.csv`: lista de entregables, fuentes, referencias, evidencias e insumos usados. Distingue qué queda incluido en GitHub y qué se conserva solo como respaldo local.
- `capitulo_21_validacion_final.json`: reporte técnico de validación del PDF final, el ZIP Overleaf, las citas IEEE, los DOI, el conteo de páginas y la corrección de la Tabla 21.3.

Estos archivos permiten reconstruir qué se usó para generar el capítulo sin publicar PDFs de artículos científicos ni documentos internos del docente.
