---
Fecha de creación: 2026-17-03 17:00
Fecha de Modificación: 2026-17-03 17:00
tags:
Topic:
---
## 📚 Idea/Concepto 

Estos son vectores de números flotantes obtenidos después de tokenizar la secuencia de entrada. Se obtienen mediante una operación de búsqueda (lookup) en una matriz de pesos entrenable, donde el ID del token actúa como índice para recuperar su vector correspondiente. El vector resultante es una representación numérica del significado del token en un espacio multidimensional, donde los ejes pueden tener significados arbitrariamente complejos. Estos valores del vector no son fijos, son parámetros que se ajustan durante el entrenamiento para optimizar la representación del lenguaje. Los tokens pueden pertenecer simultáneamente a muchos grupos basándose en características no relacionadas. Es por ello que es necesario sumarles vectores de posición para que el modelo pueda entender la estructura secuencial de la frase.

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Mecanismos de atención]]
- [[Tokenización]]
## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 