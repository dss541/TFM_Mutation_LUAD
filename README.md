# Identificación de patrones mutacionales en adenocarcinomas de pulmón (LUAD)

Este Trabajo de Fin de Máster (TFM) tiene como objetivo principal la extracción y análisis de firmas mutacionales, la identificación de genes y dominios diferencialmente expresados, así como el estudio de patrones de exclusión y coocurrencia mutacional en adenocarcinomas de pulmón con mutaciones en **KRAS** y **EGFR**. Además, se evalúa el impacto de mutaciones específicas en el pronóstico de supervivencia de los pacientes, utilizando herramientas bioinformáticas en R y datos públicos del TCGA.

---

## Estructura del proyecto

- `data/` : Datos brutos y procesados utilizados en el análisis.
- `figures/` : Figuras y gráficos generados.
- `output/` : Informes renderizados en HTML, PDF y Word.
- `results/` : Resultados tabulares y archivos auxiliares.
- `renv/` : Configuración del entorno de R para asegurar la reproducibilidad.
- `tfm_luad_kras_egfr.Rmd` : Código completo y análisis del TFM.
- `renv.lock` : Registro de las versiones exactas de los paquetes usados.

---

## Requisitos y reproducibilidad

El proyecto utiliza el paquete [`renv`](https://rstudio.github.io/renv/) para gestionar el entorno de R. Esto permite instalar las mismas versiones de paquetes que se usaron en el análisis, garantizando reproducibilidad.

Para restaurar el entorno en tu equipo:

```{r}
install.packages("renv")
renv::restore()
```
