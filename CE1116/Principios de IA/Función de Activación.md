---
Fecha de creación: 2026-17-03 17:00
Fecha de Modificación: 2026-17-03 17:00
tags:
Topic:
---
## 📚 Idea/Concepto 

Es una función matemática dentro de cada neurona de la red, que toma la suma ponderada con un sesgo (bias) como entrada y devuelve un nuevo valor de punto flotante como salida. Esta decide si se debe activar la neurona o no, introduciendo no linealidad en el modelo, estas funciones cambian su pendiente dependiendo del valor de entrada, lo que ocasiona que las neuronas tengan una respuesta ya sea amplificada, suavizada o bloqueada. Existen funciones de activación como Sigmoide, tanh, ReLU que transforman la salida de la neurona para que el modelo pueda entender relaciones complejas y no lineales del lenguaje, pero en los LLMs modernos se utilizan funciones más sofisticadas como GELU o SwiGLU, que vienen a resolver la saturación de gradientes en el aprendizaje profundo, son el estándar actual por su suavidad y rendimiento superior en tareas de lenguaje, pues permiten una mejor propagación de gradientes durante el entrenamiento de redes. El resultado de esta función es la salida de la neurona y se convierte en el input para las siguientes neuronas de la siguiente capa. Además, en la práctica, estas salidas suelen pasar por mecanismos de normalización (como Layer Normalization) para ajustar sus rangos, manteniendo la estabilidad y eficiencia durante el entrenamiento del modelo.

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Redes Neuronales]]
## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 