# Proyecto Final

Proyecto asignado en el curso **Introducción a la Ciencia de Datos con Python**.

## Requerimientos minimos

Para comprender este proyecto, se te solicitará que observes la base de datos y realices lo siguiente:

- Traduce las columnas y proporciona una idea de su posible contenido. ¿Qué representa *culmen*?
- Posteriormente, realiza un análisis exploratorio del *dataframe*, centrándote en los tipos de valores que almacenan sus columnas, la cantidad de valores `NaN` y en qué columnas se encuentran.

El siguiente paso es preparar la base de datos. Para ello, primero debes eliminar las columnas que contienen valores no numéricos. Posteriormente, rellena con la media de la columna los valores nulos o `NaN`.

Después, imprime en pantalla la matriz de correlación y posteriormente el *heatmap*. Analiza cuáles son las dos variables que presentan una correlación más alta. Recuerda importar las bibliotecas `matplotlib` y `seaborn`.

Una vez conocidas las correlaciones, te interesa visualizar la forma que tienen; por lo tanto, es necesario realizar una matriz de gráficos de dispersión.

Ahora, realiza una regresión lineal de las dos variables que consideren más significativas. Expón su coeficiente de determinación (R²) y determina si es suficientemente explicativo. En este apartado, puedes graficar la dispersión de estas dos variables junto con la línea de regresión predicha. Puedes imprimir los datos que consideres necesarios.

Luego, implementa el algoritmo de k-means para las dos variables elegidas. Como recomendación, no utilices las mismas dos variables que usaste para la regresión y plotea estos gráficos con la coloración que prefieras. 

Finalmente, realiza una regresión logística que explique el sexo del pingüino a partir del resto de variables que no son cadenas.