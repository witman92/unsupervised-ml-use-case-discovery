# Exploración de datasets y casos de uso para machine learning no supervisado

Evaluación de **10 fuentes de datos reales** (en su mayoría chilenas y abiertas) para identificar problemas relevantes que se puedan resolver con aprendizaje no supervisado, justificando su importancia y viabilidad técnica.

## Datasets evaluados
| # | Dataset | Tipo |
|---|---|---|
| 1 | Estadísticas macroeconómicas de Chile 2003-2025 ([Banco Central](https://si3.bcentral.cl/Siete/ES/Siete/Cuadro/CAP_CCNN/MN_EST_MACRO_IV/PEM_INDSEC/PEM_INDSEC)) | Tabular / series |
| 2 | Personas en RSH beneficiadas por el SUF según edad, 2025 ([BIDAT](https://bidat.gob.cl/url/68f18d8fd3e01)) | Tabular |
| 3 | Respuestas y análisis de causa de auditorías en planta de alimentos | Texto / tabular |
| 4 | [Intel Image Classification](https://www.kaggle.com/datasets/puneet6060/intel-image-classification) | Imagen |
| 5 | [Corpus de audio en español americano](https://magichub.com/datasets/american-spanish-scripted-speech-corpus-daily-use-sentence/) (4 h, 10 hablantes) | Audio |
| 6 | [Series temporales de viento](https://zenodo.org/records/5516539) | Serie temporal |
| 7 | [Índices de movilidad entre comunas](https://figshare.com/articles/dataset/Mobility_Index/13270307) | Tabular |
| 8 | [Precipitación diaria y mensual en Chile (CR2)](https://www.cr2.cl/datos-de-precipitacion/) | Serie temporal |
| 9 | [Datos sintéticos de comercio electrónico](https://www.opendatabay.com/data/synthetic/4560f7ff-a4f6-4e5f-932f-68ab5f964a2e) | Tabular |
| 10 | [Cobertura mediática digital de conflictos socioambientales](https://www.doctoradoencomunicacion.cl/repositorio/s/principal/item/217) | Texto (redes sociales) |

## Casos de uso seleccionados
Para cada uno se resume el contenido, el problema real que resuelve, la técnica no supervisada propuesta (K-means, PCA, etc.) y los desafíos (faltantes, desbalance, costo computacional):
- **Texto:** análisis de causa de auditorías en planta de alimentos.
- **Tabular / serie temporal:** viento horario.
- **Imagen:** Intel Image Classification.

## Estructura
```
dataset_exploration_use_cases.ipynb
1.- … 10.- Dataset …            # Archivos de datos evaluados
```

**Stack:** Python · pandas · Pillow
