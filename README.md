# Proyecto integrador HMM-ASR

## Tema

**Modelos ocultos de Markov y evolución hacia modelos híbridos y profundos en reconocimiento automático de voz.**

## Pregunta de investigación

¿Cómo se utilizan los modelos ocultos de Markov y sus enfoques derivados en el reconocimiento de voz?

## Objetivo general

Analizar el uso de los modelos ocultos de Markov (HMM) y sus enfoques derivados en sistemas de reconocimiento automático de voz, considerando su evolución hacia arquitecturas híbridas y su aplicación en condiciones acústicas adversas o de bajo recurso.

## Herramientas

- **Overleaf / LaTeX:** documento académico editable.
- **Mendeley:** organización bibliográfica y exportación de referencias seleccionadas.
- **Scopus:** corpus documental recuperado en la etapa previa de búsqueda.
- **GitHub:** trazabilidad de la estructura y evolución del proyecto.

## Estructura del repositorio

```text
.
├── docs/    Documento LaTeX, PDF compilado y activo institucional.
├── refs/    Bibliografía IEEE curada, limitada a las fuentes citadas.
├── data/    Alcance de los datos y del corpus documental.
└── src/     Espacio previsto para una futura fase experimental.
```

## Documento

El archivo editable principal es [`docs/proyecto_integrador_hmm_asr.tex`](docs/proyecto_integrador_hmm_asr.tex).  
Para trabajarlo en Overleaf se debe cargar `docs/proyecto_integrador_hmm_asr.tex`, `docs/logo_unl.png` y `refs/referencias_hmm_asr_curadas.bib`, conservando la estructura de carpetas.

## Capítulo final de libro

La versión final del capítulo individual está organizada en [`docs/capitulo_21_libro/`](docs/capitulo_21_libro/).

Entregables principales:

- PDF final validado: [`docs/capitulo_21_libro/Capitulo_21_HMM_ASR_Limpio_AntiIA_10Paginas_Final.pdf`](docs/capitulo_21_libro/Capitulo_21_HMM_ASR_Limpio_AntiIA_10Paginas_Final.pdf).
- ZIP final para Overleaf: [`docs/capitulo_21_libro/Capitulo_21_HMM_ASR_Limpio_AntiIA_10Paginas_Overleaf.zip`](docs/capitulo_21_libro/Capitulo_21_HMM_ASR_Limpio_AntiIA_10Paginas_Overleaf.zip).
- Fuente LaTeX final: [`docs/capitulo_21_libro/overleaf_package/`](docs/capitulo_21_libro/overleaf_package/).
- Validación final: [`data/capitulo_21_validacion_final.json`](data/capitulo_21_validacion_final.json).
- Registro de materiales usados: [`data/capitulo_21_materiales_usados.csv`](data/capitulo_21_materiales_usados.csv).

## Trazabilidad bibliográfica

La búsqueda previa en Scopus recuperó 321 registros relacionados con HMM y reconocimiento de voz. Por integridad y claridad del proyecto, este repositorio separa dos niveles de bibliografía: la bibliografía efectivamente citada en el documento principal y el corpus activo de 28 fuentes seleccionadas.

- Bibliografía citada en el documento: [`refs/referencias_hmm_asr_curadas.bib`](refs/referencias_hmm_asr_curadas.bib).
- Corpus bibliográfico activo de 28 fuentes: [`refs/fuentes_hmm_asr_28.bib`](refs/fuentes_hmm_asr_28.bib).
- Bibliografía IEEE final del capítulo de libro: [`refs/capitulo_21_referencias_ieee.bib`](refs/capitulo_21_referencias_ieee.bib).
- Tabla de metadatos y estado local de PDFs: [`data/fuentes_hmm_asr_28.csv`](data/fuentes_hmm_asr_28.csv).

Los PDFs completos se conservan como respaldo académico local y no se publican en GitHub.

## Evidencias de la práctica

La trazabilidad de la APE 007, incluidos los enlaces a los notebooks solicitados por el docente, se registra en [`docs/evidencias_ape007.md`](docs/evidencias_ape007.md).

## Estado

Estructura inicial del proyecto integrador creada para la Actividad Práctico-Experimental Nro. 007 de la asignatura **Metodología de la Investigación en Computación**.

Actualización posterior: se incorporó la versión final validada del **Capítulo 21: Modelos Ocultos de Markov (HMM) y su aplicación en el reconocimiento automático de la voz**, con PDF, ZIP Overleaf, fuente LaTeX, bibliografía IEEE y reporte de validación.
