# TA-IND-04 — Informe Técnico Individual

**Estudiante:** Robinson Rodrigo Cando Moreno
**Universidad:** Universidad Técnica Estatal de Quevedo
**Facultad:** Ciencias de la Computación
**Carrera:** Ingeniería de Software
**Asignatura:** Aplicaciones Distribuidas (ISR-701)
**Docente:** Gleiston C. Guerrero-Ulloa, M.Sc.
**Período:** 2026–2027 PPA

## PFC de referencia
- **Código:** ACC
- **Título del sistema:** Sistema de Gestión de Soporte Técnico ISP

## Equipo de PE-U4
Cristhian Daniel Pacheco Cárdenas, Robinson Rodrigo Cando Moreno, Ernesto Gregory Luna Mora

## Transformación declarada como foco individual
**T1 — Filtrado y selección**

## Origen de los datos base
- **Repositorio de PE-U4 (equipo):** https://github.com/CristhianP03/pe-u4-spark-equipoA
- **Commit:** `19e84a0072f1fe49a53d1e5b71b17ba8d83091b3`
- **Nota de trazabilidad:** los tiempos de T1 en N=1 y N=2 no están en el commit anterior (el equipo solo escaló T3). Fueron medidos individualmente por el autor con el mismo protocolo (`medicion.py`: 1 calentamiento + 5 repeticiones, mediana) y se incluyen en `datos/tiempos_base.csv` de este repositorio.

## Estructura del repositorio
ta-ind-04-cando/
├── README.md
├── LICENSE
├── docs/
│   ├── TA_IND_04_Informe.tex
│   ├── TA_IND_04_Informe.pdf
│   └── references.bib
├── datos/
│   └── tiempos_base.csv
└── figuras/
    └── fig_speedup.png
## Instrucciones de compilación
Requiere pdflatex y biber (distribución LaTeX completa, ej. TeX Live o MiKTeX).

    cd docs
    pdflatex TA_IND_04_Informe.tex
    biber TA_IND_04_Informe
    pdflatex TA_IND_04_Informe.tex
    pdflatex TA_IND_04_Informe.tex

## Declaración de uso de inteligencia artificial generativa
*(pendiente — se completa junto con el informe)*
