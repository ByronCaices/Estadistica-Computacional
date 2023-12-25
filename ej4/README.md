_Author: Byron Caices_

# Visualización de Datos en Online Retail

## Descripción

Este proyecto utiliza un Shiny App incrustado en un documento R Markdown para visualizar datos del conjunto de datos "Online Retail". Se pueden visualizar dos tipos de gráficas:

1. Distribución de precios unitarios (`UnitPrice`).
2. Frecuencia de registros por país (`Country`).

## Requisitos

- R
- RStudio (recomendado para facilitar la ejecución)

## Librerías necesarias

Para ejecutar el código correctamente, necesitas instalar las siguientes librerías en R:

- `shiny`
- `ggplot2`
- `readxl`

Puedes instalarlas usando el siguiente código en R:

```R
install.packages("shiny")
install.packages("ggplot2")
install.packages("readxl")
```

## Cómo ejecutar el código

1. **Abrir el archivo `.Rmd` en RStudio**: Si aún no tienes RStudio, es recomendable que lo descargues e instales desde [aquí](https://rstudio.com/products/rstudio/download/).

2. **Instalar las librerías**: Si aún no has instalado las librerías mencionadas, puedes hacerlo directamente desde la consola de RStudio.

3. **Ejecutar el Shiny App**: Una vez abierto el archivo `.Rmd` en RStudio y después de asegurarte de que todas las librerías están instaladas, puedes ejecutar el Shiny App haciendo clic en el botón "Run Document" que se encuentra en la parte superior del editor de scripts.

### Cómo usar la interfaz

1. **Seleccionar una gráfica**: Utiliza las opciones de radio para seleccionar la gráfica que deseas visualizar. Las opciones son "Distribución de precios unitarios" y "Frecuencia de registros por país".

2. **Ver la gráfica**: Una vez seleccionada la opción, la gráfica correspondiente se mostrará en el panel principal de la aplicación.

