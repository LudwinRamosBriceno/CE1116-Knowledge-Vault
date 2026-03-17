---
Fecha de creación: 2026-17-03 17:00
Fecha de Modificación: 2026-17-03 17:00
tags:
Topic:
---
## 📚 Idea/Concepto 

Componente principal de la arquitectura Transformer. El modelo lo utiliza para decidir en qué parte de la entrada prestar atención al procesar cada palabra. Este proceso se puede realizar en paralelo para cada una de las entradas o palabras, y tiene 4 pasos: transformar las entradas en tensores de query, key y value mediante cálculos a partir de los embeddings de tokens y pesos aprendidos, mapear cada query contra un conjunto de keys para determinar la relevancia de los values correspondientes mediante la generación de puntuaciones o pesos de atención, utilizar las puntuaciones para escalar los values, y por último sumar los values escalados para generar una nueva salida para cada entrada.
Concretamente, cuando el modelo procesa un token (una palabra) este genera un query y lo compara con las keys de todos los demás tokens de entrada, esto lo hace con un producto punto. Dicha comparación genera puntuaciones que luego pasan por un factor de escalado mediante una división y luego por la función Softmax, que las normaliza convirtiéndolas en probabilidades (pesos de atención que suman 1) y determinan la relevancia de cada entrada (palabras en la frase). Con esos pesos se realiza un promedio ponderado de los values de todas las palabras, así el modelo dará mucho peso a ciertas palabras y de esa forma capturará el contexto de la secuencia de entrada. Este proceso se realiza simultáneamente en múltiples "heads" de atención paralelas (multi-head attention), lo que permite al modelo capturar diferentes aspectos relacionales del texto (como relaciones gramaticales, semánticas o sintácticas).

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Arquitectura Transformer]]
- [[Embeddings]]
## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 