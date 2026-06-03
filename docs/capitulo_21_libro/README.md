# Capítulo 21: HMM-ASR — versión final de libro

Esta carpeta conserva la versión final del capítulo de libro sobre **Modelos Ocultos de Markov (HMM) y su aplicación en el reconocimiento automático de la voz**.

## Entregables

- `Capitulo_21_HMM_ASR_Limpio_AntiIA_10Paginas_Final.pdf`: PDF final validado.
- `Capitulo_21_HMM_ASR_Limpio_AntiIA_10Paginas_Overleaf.zip`: paquete final para subir a Overleaf.
- `overleaf_package/`: fuente LaTeX descomprimida y trazable.
- `CHECKSUMS.sha256`: huellas de integridad de PDF, ZIP y fuentes.

## Fuente editable

La fuente final está en:

```text
overleaf_package/
├── main.tex
├── referencias.bib
└── capitulos/
    └── capitulo_21.tex
```

Para compilar localmente con Tectonic:

```bash
cd docs/capitulo_21_libro/overleaf_package
tectonic -X compile main.tex
```

Para trabajar en Overleaf, subir el ZIP final o cargar los tres archivos respetando la estructura de carpetas.

## Validación final

El reporte completo está en `../../data/capitulo_21_validacion_final.json`.

Resumen validado el 03 de junio de 2026:

- 13 páginas totales.
- 10 páginas de contenido antes de referencias.
- Referencias desde la página 11.
- 25 referencias IEEE.
- 25 citas usadas.
- 0 citas indefinidas.
- 0 referencias sin citar.
- 25 DOI visibles y 25 URLs DOI únicas en el PDF.
- 0 apariciones de `£` en la Tabla 21.3; los signos `¿` renderizan correctamente.
- Compilación LaTeX desde la fuente sin errores, citas indefinidas ni overfull/underfull detectados.

## Criterio ético de archivo

Los PDFs completos de artículos, el PDF modelo del docente y otros insumos externos no se publican en GitHub. Quedan registrados en `INSUMOS_USADOS.md` y en `../../data/capitulo_21_materiales_usados.csv` para trazabilidad sin subir material de terceros.
