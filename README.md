# Topico1
El proyecto del curso consiste en la aplicación de los conceptos vistos durante el
curso Ciencia de Datos en diversos tópicos, principalmente los algoritmos de
hallazgo de patrones frecuentes. Específicamente la tarea es:
1. Encontrar itemsets frecuentes usando FP-Growth con tamaños 3 a 10
itemset.
2. Efectuar estrategias para mejorar velocidad de algoritmos. Pruebe:
a. K particiones random de data.
b. Aplicar K means sobre datos.
c. Aplicar K means sobre datos de forma repetida tal que en cada
iteración se quede con cluster con mayor varianza. Luego remover
datos, y aplicar K means con K=K-1 siguiendo misma lógica. Asi
hasta que queden K=2 y quedarse con los dos clusters resultantes.
3. Experimentar:
a. Tiempo vs soporte minimo.
b. Tiempo vs K para cada método en parte 2, donde K va desde 2 a
20 en pares (solo parte 2)
c. Confianza promedio vs K para cada método en parte 2, donde K va
desde 2 a 20 en pares (solo parte 2).
d. Diversidad promedio vs K para cada método en parte 2, donde K
va desde 2 a 20 en pares (solo parte 2).
Considere como medida de diversidad a la entropía de Shannon (Ver Anexo).
Use el promedio de la entropía de cada ítem considerando todos los itemsets
hallados por algoritmos. Puede usar cualquier librería disponible en la Web.
La base de datos a testear es:
- Bases de datos de mercado online:
https://www.instacart.com/datasets/grocery-shopping-2017
 Adicionalmente ustedes puede proponer un proyecto relacionado con curso,
de preferencia basados en imágenes. Hitos a definir.
 En parte 2, tiene la opción de proponer una nueva estrategia para encontrar
reglas con alta diversidad como alto soporte. De tener éxito tiene bono de
+0.5 en nota final de proyecto. Si superan 7, ese bono equivale a aumento
de 0.25 en Solemne 3 de curso.




Esta actividad consiste en múltiples hitos. En particular se le pide de forma
incremental y monotónica en calidad:
a. Análisis y preprocesamiento de datos (8/5 a las 11:59 pm, peso: 15%)
i. Definición de proyecto
ii. Descripción de datos
iii. Análisis 1D y 2D de datos.
iv. Preprocesamiento de datos.
b. Implementación de algoritmos automáticos (29/5 a las 11:59 pm, peso: 25%)
i. Revisión de métodos relacionados con tarea, al menos 3
trabajos después del 2000.
ii. Descripción de algoritmo propuesto para tarea
iii. Implementación de algoritmo propuesto para tarea (partes 1,
3-a).
c. Resultados de implementación (17/6 a las 11:59 pm, peso: 40%)
i. Revisión de métodos relacionados con tarea, al menos 3
trabajos después del 2010.
ii. Implementación de algoritmo propuesto para tarea (partes 2,
3-b,3-c y 3-d).
iii. Resultados de implementación en datos
iv. Conclusiones de resultados
d. Exposición final de proyectos (fecha a definir a partir del 18/6, peso: 20%)
i. Presentación de grupal de proyectos.
 Fecha a sortear en últimas semanas de curso.
 Duración máxima 20 minutos.
 Tiempo para preguntas: 3 minutos
 Notas tanto individual como grupal.
Nótese que se ha indicado la fecha y ponderación de cada fase. La nota de este
proyecto equivale a nota de Tarea de curso.
En cada entrega deben entregar dentro de archivo ZIP:
1. La documentación, la cual contendrá al menos 7 páginas,
preferentemente con impresiones de pantallas, y un máximo de 25
páginas. Se recomienda el uso de Latex, pero no es obligatorio. Una
página debe ser para caratula. El informe se debe entregar en formato
Latex así como PDF.
2. Código fuente de avances de proyectos.
Se debe enviar archivo ZIP a correo de profesor: billy.peralta@unab.cl.
Opcionalmente pueden usar servicios en la nube si los archivos fueran muy
voluminosos. El mínimo/máximo de alumnos por grupo es de 2/4 integrantes.
