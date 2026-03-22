# TODO list
- El fichero Rmd (fichero fuente con el código y el texto) []
- El fichero de salida del Rmarkdown, es decir, el informe que genera, en formato html o en PDF. []
- El fichero de datos después del preproceso. []

Para facilitar la corrección incluid vuestro apellido en los nombres de los ficheros, de la siguiente forma:

- apellido_preproceso.Rmd
- apellido_preproceso.html o apellido_preproceso.pdf
- apellido_fichero_clean.csv

Cuando realicéis el informe, debéis incluir para cada paso del enunciado:

- La pregunta particular a la que se quiere dar respuesta
- El código R utilizado 
- La salida del código R
- Una explicación (si es necesaria) que complemente el resultado del código R.

Para mejor estructuración del código, se aconseja desarrollar cada una de las preguntas en un fragmento distinto (code chunk) de código R.

Es imprescindible que el informe se realice mediante la herramienta RMarkdown que permite generar informes dinámicos. En la actividad 0 tenéis instrucciones y ejemplos de cómo realizar un informe dinámico.

Es muy importante que recordéis que no se corregirán entregas que contengan listados de datos de más de 1 página, puesto que genera informes muy largos y difíciles de seguir. En su lugar, podéis mostrar la cabecera del fichero (usando la función head de R) o sólo los cambios realizados. 

No se corregirán entregas que sólo contengan el fichero .Rmd. El motivo es que para poder corregirlos, estos ficheros se deben ejecutar y al ejecutarlos pueden contener errores o puede que sea necesaria la instalación de librerías. A la hora de corregir, el profesor no puede subsanar estos posibles errores. Es por esto que debéis entregar el fichero de salida PDF o HTML donde se muestre la salida de la ejecución del código pertinente. El fichero RMD que entregáis sólo se usa para comprobaciones complementarias. Pero la revisión se realiza principalmente sobre el fichero de salida PDF o HTML.