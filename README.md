# topico1
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
