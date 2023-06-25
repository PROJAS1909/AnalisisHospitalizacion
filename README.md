Análisis de pacientes hospitalizados
Planteamiento de la problemática

Se nos ha solicitado el análisis de un datasets que contiene información de pacientes masculinos en un rango etario de entre 39 y 84 años, a los cuales se les ha realizado biopsias prostática por diferentes causas, sin embargo el equipo médico a notado que existe un grupo de pacientes que está siendo hospitalizado sin causa aparente, por lo cual se nos indica que analicemos los mismos en búsqueda de una causa aparente.

Hipótesis:
Existe una relación entre los datos que permita determinar las hospitalizaciones

Para poder llevar a cabo el proceso, se realizó un análisis exploratorio de los datos, seguido de una normalización, al hacer esto procedimos a realizar una matriz de correlación entre las diferentes variables logrando encontrar que la presencia o no de comorbilidades no era una causa aparente de hospitalización, tampoco se encontró relación entorno a edad o valores de PSA sin embargo, se logró observar una dependencia entre el número de muestras tomadas durante la biopsia y las hospitalizaciones entre los paciente. Esto es denotado gracias a una matriz de correlación y confirmado visualmente con un mapa de calor. No obstante procedimos a realizar un modelo de machine learning supervisado y de clasificación para evaluar si lo visualmente encontrado era certero.

Partiendo de esto y continuando con el modelo realizamos un análisis de random forest que efectivamente concluyó que existía una predicción del 94% para esta variable, en este sentido logramos cumplir y confirmar nuestra hipótesis que puede en un futuro disminuír el número de pacientes que culminan en hospitalización, dando así un resultado certero para disminuir la tasa de hospitalización.

En otro orden de ideas en base al datasets con 540 datos obtuvimos que 24 eran hospitalizados y que todos ellos sin importar la profilaxis antibiótica utilizada, las comorbilidades existentes etc, presentaban hospitalización si se tomaban más de 12 muestras durante la biopsia.

Adicionalmente encontrará un dashboard en power bi, donde podrá denotar mejor el análisis de los datos.
