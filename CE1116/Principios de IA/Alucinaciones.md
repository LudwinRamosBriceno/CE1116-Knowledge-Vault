---
Fecha de creación: 2026-17-03 17:00
Fecha de Modificación: 2026-17-03 17:00
tags:
Topic:
---
## 📚 Idea/Concepto 

Es un fenómeno en el que un modelo de LLM percibe patrones u objetos inexistentes, inventando información falsa que presenta con seguridad. Esto ocurre porque el objetivo de esta es generar una respuesta a partir de los patrones que aprendió en su entrenamiento, a pesar de que la información utilizada en su ventana de contexto no sea suficiente. Sin embargo, existe un matiz importante, el modelo como tal no intenta rellenar huecos de forma deliberada o consciente, simplemente predice el token estadísticamente más probable según la distribución de su entrenamiento, no comprende si lo que dice es verdadero o es falso, solo evalúa qué palabra es más probable (verosimilitud) porque ha aprendido que ciertas palabras suelen aparecer juntas en contextos similares. Esto se debe a que los LLM no poseen una base de datos de hechos, sino asociaciones estadísticas almacenadas en sus pesos (especialmente en las capas feed-forward), el modelo carece de un mecanismo de verificación externa a la realidad, operando puramente en un espacio de tokens y generando texto basado únicamente en probabilidades. También se puede dar que en el entrenamiento haya datos contradictorios o ruido que genere una raíz de patrones erróneos.

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
-  [[Ventana de Contexto]]
## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 