<p align="center">
  <img src="banner.svg" alt="Math Crush banner" width="100%">
</p>

<h1 align="center">🧮 Math Crush</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Género-Puzzle%20%2F%20Arcade-8a2be2?style=for-the-badge">
  <img src="https://img.shields.io/badge/Motor-HTML5%20%2F%20CSS3%20%2F%20JavaScript-00f5ff?style=for-the-badge">
  <img src="https://img.shields.io/badge/Estado-Jugable-00ff88?style=for-the-badge">
</p>

## 📖 Descripción

**Math Crush** es un puzzle arcade de matemática rápida con estética *RGB Gamer*. El jugador debe encontrar el **número objetivo** que se muestra en pantalla combinando dos celdas **vecinas** del tablero mediante una operación matemática (suma, resta, multiplicación o división).

- **¿De qué trata?** De resolver operaciones matemáticas contrarreloj para acumular la mayor cantidad de puntos posible antes de quedarte sin tiempo o sin vidas.
- **Objetivo del jugador:** Formar el número objetivo combinando dos números adyacentes del tablero con la operación correcta, antes de que se acabe el tiempo (60s) o las 3 vidas.
- **Mecánica principal:** Selección de dos celdas vecinas del tablero (arriba, abajo, izquierda o derecha) + elección de operador (+, −, ×, ÷). Si el resultado coincide con el objetivo, las celdas explotan, se suman 100 puntos y el tablero se recompone (efecto tipo "match" en cascada).

## 🎮 Controles

| Acción | Control |
|---|---|
| Seleccionar número | `CLICK` sobre una celda del tablero |
| Elegir operación | `CLICK` sobre el botón +, −, × o ÷ |
| Reiniciar selección | `CLICK` en una tercera celda no vecina |

## 🛠️ Tecnologías

- HTML5
- CSS3 (gradientes, glassmorphism, animaciones y diseño responsive)
- JavaScript vanilla (lógica de juego, temporizador y generación de tableros)

## 📸 Capturas de pantalla

| Pantalla inicial | Gameplay | Game Over |
|---|---|---|
| ![inicio](../../assets/screenshots/masth-crush-inicio.png) | ![gameplay](../../assets/placeholder.svg) | ![gameover](../../assets/placeholder.svg) |

## ▶️ Jugar

Abre [`index.html`](./index.html) en tu navegador, o pruébalo en vivo (se abre en pestaña nueva) vía GitHub Pages:

<a href="https://TheStevenTL.github.io/MiPortafolioGameDevelopment/games/math-crush/" target="_blank" rel="noopener">https://TheStevenTL.github.io/MiPortafolioGameDevelopment/games/math-crush/</a>

## 💡 Qué aprendí

- Diseño de un sistema de generación procedural de retos matemáticos con solución garantizada.
- Manejo de estados de UI (pantallas de inicio, juego y fin) con transiciones suaves en JavaScript puro.

## 🔧 Qué mejoraría en una siguiente versión

- Añadir niveles de dificultad progresiva y un modo contrarreloj más largo.
- Sumar un sistema de combos y power-ups.
- Guardar puntajes máximos con `localStorage`.

---
⬅️ [Volver al portafolio principal](../../README.md)
