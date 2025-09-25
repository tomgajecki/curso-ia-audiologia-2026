# Estadística avanzada, IA y Big Data en Audiología (Ed. 2026)

**Docente:** Tom Gajecki  
**Duración:** 19 enero – 6 febrero 2026  
**Carga horaria:** 18 h (8 h presencial, 10 h virtual)  

Este repositorio contiene el material del curso, incluyendo *notebooks* ejecutables, datasets simulados y recursos para las sesiones virtuales y presenciales.

## Estructura del repo
```
curso-ia-audiologia-2026/
├── README.md
├── environment.yml           # o requirements.txt
├── .gitignore
├── data/
│   ├── raw/                  # datos simulados/anonimizados (añadir aquí)
│   └── processed/
├── notebooks/
│   ├── 01_intro_ia_audiologia.ipynb
│   ├── 02_bigdata_exploratorio.ipynb
│   ├── 03_lab_clasificacion.ipynb
│   ├── 04_med_personalizada_logit_roc.ipynb
│   ├── 05_modelos_comparados_y_tests.ipynb
│   ├── 06_lab_prediccion_eficacia_anova_tukey.ipynb
│   ├── 07_anonimizacion_y_sesgos.ipynb
│   └── 08_sesgo_simulado_y_mitigacion.ipynb
└── slides/
```

## Cómo ejecutar los notebooks

### Opción A) Binder (recomendada)
1. Sube este repositorio a GitHub (público).
2. Ve a [https://mybinder.org](https://mybinder.org), introduce la URL de tu repo y lanza el entorno.
3. Abre los notebooks desde la carpeta `notebooks/`.

### Opción B) Google Colab
1. Sube este repositorio a GitHub.
2. En Colab, usa *File > Open Notebook > GitHub* y pega la URL del repo.
3. Instala dependencias con `pip -r requirements.txt` si lo necesitas.

> **Nota:** No subas datos personales. Usa solo datos simulados o anonimizados.

## Requisitos/Entorno
El curso usa Python 3.10+ y las librerías:
- pandas, numpy, matplotlib, scikit-learn, statsmodels, scipy, jupyterlab

Puedes usar `environment.yml` (Conda) **o** `requirements.txt` (pip).

## Calendario (resumen)
- **Semana 1:** IA y Big Data (19/01, 21/01, 23/01)  
- **Semana 2:** Medicina personalizada (26/01, 28/01, 30/01)  
- **Semana 3:** Ética e interoperabilidad (02/02, 04/02, 06/02)  

## Evaluación (resumen)
- Participación y ejercicios: 10%  
- Estudios de caso: 10%  
- Examen parcial (30 ene): 10%  
- Laboratorios (23, 30 ene; 6 feb): 30%  
- Examen final (6 feb): 40%

## Créditos y Licencia
© 2026 Tom Gajecki. Ajusta la licencia si quieres hacerlo abierto (p.ej., CC BY 4.0).