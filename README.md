# ACAO - Algoritmo Integrado de Detección de Explosiones Volcánicas

Este proyecto implementa un algoritmo automático de detección y segmentación de explosiones volcánicas, basado en el análisis de conglomerados de amplitud de onda (ACAO). Utiliza datos sísmicos y acústicos mediante bibliotecas como ObsPy, SciPy y Scikit-learn.

## Características principales

- Sustituye los métodos clásicos como STA/LTA por una lógica basada en conglomerados de amplitud  y  el acoplamiento acústico
- Procesamiento de una señal sísmica y dos acústicas (SMP, IST, ISA)
- Detección y segmentacion de explosiones volcánicas
- Análisis de similitud entre componentes acústicas
- Generación de archivos Excel con los resultados de detección

## Requisitos

- Python 3.8+
- ObsPy
- NumPy
- Pandas
- Matplotlib
- SciPy
- Scikit-learn
- Seaborn
- Colorama

Puedes instalar los requerimientos con:

```bash
pip install -r requirements.txt
