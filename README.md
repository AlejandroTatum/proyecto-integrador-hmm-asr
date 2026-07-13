# Proyecto integrador HMM-ASR

Investigación académica sobre el uso de modelos ocultos de Markov en reconocimiento automático de voz y su evolución hacia arquitecturas híbridas y profundas. El repositorio reúne el documento editable, la bibliografía curada y la evidencia de trazabilidad del trabajo.

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

## Uso local

### Requisitos

- Una distribución de LaTeX, como TeX Live, o una cuenta de Overleaf.
- BibTeX para procesar las referencias.

### Compilar el documento principal

```bash
git clone https://github.com/AlejandroTatum/hmm-speech-recognition-research.git
cd hmm-speech-recognition-research
pdflatex -output-directory=docs docs/proyecto_integrador_hmm_asr.tex
bibtex docs/proyecto_integrador_hmm_asr
pdflatex -output-directory=docs docs/proyecto_integrador_hmm_asr.tex
pdflatex -output-directory=docs docs/proyecto_integrador_hmm_asr.tex
```

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


## Portafolio digital Unidad 1

El cierre de la Unidad 1 está organizado en [`docs/portafolio_unidad_1/`](docs/portafolio_unidad_1/). Incluye el reporte técnico de autoevaluación reflexiva, los productos PDF de la unidad, evidencias de integridad e inventario de productos.

- Reporte final: [`docs/portafolio_unidad_1/portafolio_unidad1_autoevaluacion.pdf`](docs/portafolio_unidad_1/portafolio_unidad1_autoevaluacion.pdf).
- Inventario: [`data/portafolio_unidad_1_productos.csv`](data/portafolio_unidad_1_productos.csv).

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

Proyecto académico desarrollado para la asignatura **Metodología de la Investigación en Computación**. No es una implementación de un sistema de reconocimiento de voz en producción.

Actualización posterior: se incorporó la versión final validada del **Capítulo 21: Modelos Ocultos de Markov (HMM) y su aplicación en el reconocimiento automático de la voz**, con PDF, ZIP Overleaf, fuente LaTeX, bibliografía IEEE y reporte de validación.
