# 🐍 Snake Game - Java Swing

Este proyecto es una implementación básica del clásico juego **Snake**, programado en **Java** utilizando la librería **Swing** para la interfaz gráfica.

---

## 🎮 Características principales

- ✅ **Grilla dinámica:** El área de juego está dividida en una cuadrícula visible y configurable.
- ✅ **Movimiento de la serpiente:** Controla la dirección usando las teclas:
  - `W` → Arriba
  - `A` → Izquierda
  - `S` → Abajo
  - `D` → Derecha
- ✅ **Generación de manzanas:** Las manzanas aparecen en posiciones aleatorias dentro de la grilla.
- ✅ **Puntaje:** Cada manzana comida incrementa la longitud de la serpiente y suma puntos.
- ✅ **Detección de colisiones:** El juego termina si la serpiente choca consigo misma o con los bordes de la ventana.
- ✅ **Reinicio del juego:** Al finalizar la partida, puedes reiniciar presionando la tecla `Enter`.

---

## ⚙️ Funcionamiento

- Al iniciar la aplicación, el juego comienza automáticamente.
- Un **Timer** controla la velocidad de movimiento de la serpiente.
- Los controles de teclado permiten cambiar la dirección en tiempo real.
- Cuando la serpiente colisiona con los bordes o consigo misma, se detiene la partida y se muestra un mensaje **Game Over** junto con la puntuación final.
- Presionando `Enter` se reinicia la partida desde cero.

---

## 🚀 Cómo ejecutar

1. **Compilar:**  
   ```bash
   javac *.java
   ```
