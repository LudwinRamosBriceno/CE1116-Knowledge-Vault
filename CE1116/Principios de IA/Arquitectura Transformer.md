---
Fecha de creación: 2026-17-03 17:00
Fecha de Modificación: 2026-17-03 17:00
tags:
Topic:
---
## 📚 Idea/Concepto 

Es un tipo de arquitectura de las redes neuronales modernas, que se basa en mecanismos de atención (self-attention), que permiten procesar secuencias completas en paralelo, dado que captura relaciones globales entre elementos; es decir, que al procesar una palabra, mira al mismo tiempo todas las otras palabras en la frase para capturar el contexto. Al procesar en paralelo, el modelo es agnóstico al orden (no lo contempla), por lo que se debe sumar vectores de posición a las representaciones de entrada para que pueda entender la estructura secuencial del lenguaje. El mecanismo de atención se divide además en múltiples "cabezas" paralelas (multi-head attention), lo que permite al modelo capturar simultáneamente diferentes aspectos relacionales del texto, como relaciones gramaticales, semánticas o sintácticas. Esta arquitectura no se limita a tres capas como una red neuronal clásica, sino que está compuesta por un stack de múltiples capas, que pueden ser bloques de Encoders, Decoders o una combinación de ambos, donde cada bloque contiene mecanismos de atención y redes feed-forward. Además, cada subcapa dentro del bloque está envuelta en una Residual Connections (skip connections) que suma la entrada original a la salida de la subcapa, seguida de una Layer Normalization. En ingeniería, estas conexiones residuales y normalizaciones son vitales para estabilizar el entrenamiento y permitir que el gradiente fluya adecuadamente a través de stacks profundos, evitando problemas perdida del gradiente.

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Redes Neuronales]]
- [[Mecanismos de atención]]
## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 