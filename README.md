# 🎲 Juego del Caos (Chaos Game)

Este repositorio muestra cómo generar la **representación del Juego del Caos**, un método iterativo para construir figuras fractales (como el triángulo de Sierpinski) a partir de reglas simples.

---

## 📌 ¿Qué es el Juego del Caos?

El **Juego del Caos** es un algoritmo que:

1. Elige un polígono inicial (por ejemplo, un triángulo).  
2. Selecciona un punto aleatorio dentro de él.  
3. Repite muchas veces el siguiente paso:  
   - Escoge al azar un vértice del polígono.  
   - Mueve el punto actual hacia ese vértice una fracción de la distancia (generalmente 1/2).  
   - Dibuja el nuevo punto.  

Con suficientes iteraciones, emergen patrones **fractales** como el **Triángulo de Sierpinski**.  
