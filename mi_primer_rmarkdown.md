Mi primer R Markdown
================

Hola! soy un archivo R Markdown

# Sección 1

Este es un **chunk de código** que muestrea 100 observaciones de una
*distribución normal*:

``` r
muestra <- rnorm(100)

length(muestra)
```

    ## [1] 100

# Sección 2

También puedo cálcular la media (promedio) de la muestra.

La media es 0.1639047
