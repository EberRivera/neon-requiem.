
# ⬛⬜ NEON REQUIEM — THE LAST ECHO ⬜⬛

**A high-octane, twin-stick arena survival game built strictly under 32 KB.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Canvas 2D](https://img.shields.io/badge/Canvas_2D-black?style=for-the-badge)
![Web Audio API](https://img.shields.io/badge/Web_Audio_API-blue?style=for-the-badge)

## 🎮 Play the game
[**[ JUGAR AHORA / PLAY NOW ]**](https://eberrivera.github.io/neon-requiem./)

---

## 💻 El Reto de los 32 KB (Technical Overview)
Este proyecto fue desarrollado cumpliendo estrictamente con las reglas de desarrollo de 32 KB:
- **Cero dependencias:** No se utilizan motores gráficos (ni Phaser, ni PixiJS, ni Unity). Todo está escrito en **JavaScript Vanilla** desde cero, utilizando `Canvas 2D`.
- **Cero assets externos:** No hay imágenes (`.png`, `.jpg`) ni fuentes descargadas. Todos los gráficos, personajes, animaciones y sistemas de partículas se dibujan proceduralmente en tiempo real mediante matemáticas y geometría.
- **Audio Procedural (Sintetizador Web):** No hay archivos `.mp3` ni `.wav`. Todos los efectos de sonido y la música de fondo son generados en tiempo real manipulando osciladores con la **Web Audio API**.
- Todo el código (HTML, CSS y JS) está comprimido en un único archivo `index.html` que pesa **menos de 15 KB**.

## 📖 Lore: La Anomalía
La simulación está colapsando. Las purgas rutinarias están borrando toda la conciencia digital. Pero una anomalía se niega a ser eliminada: **ZERO**, un humano atrapado dentro del código. 

Ante la aniquilación inminente, la pura fuerza de voluntad y los recuerdos de ZERO se han materializado fuera de su cuerpo físico como una entidad etérea—su alma proyectada como un arma: **WHITE NOISE**. Mientras ZERO dispara para defenderse, WHITE NOISE ejecuta golpes cuerpo a cuerpo y altera la realidad de la simulación. 

Sobrevive a 10 oleadas de antivirus corruptos y enfréntate a la inteligencia central: **THE FIRST**.

## ⌨️ Controles
*   **W, A, S, D:** Mover a ZERO.
*   **Ratón (Mouse):** Apuntar.
*   **Clic Izquierdo (Mantener):** Disparo de ráfaga (ZERO) + Golpes cuerpo a cuerpo (WHITE NOISE).
*   **Espacio (Space):** *Phantom Shift* - Intercambia posición instantáneamente con tu alma para esquivar ataques letales.
*   **Q:** *Modo y Soul Break* - Cambia la distancia de tu alma (Guardia/Asalto). Si el enfriamiento (8s) está listo, detona una enorme onda expansiva.
*   **E:** *Requiem State* - Congela el tiempo y a los enemigos durante 2 segundos (Enfriamiento: 25s).
*   **ESC / P:** Pausar el juego.

## 🛠️ Instalación / Ejecución Local
No requiere instalación, dependencias de Node.js, ni servidores locales. 
Simplemente descarga el repositorio y abre el archivo `index.html` en cualquier navegador web moderno (Chrome, Firefox, Edge).

## 🌍 Idiomas / Localization
El juego cuenta con un sistema de traducción dinámico e incluye soporte completo en **Inglés** y **Español** directamente desde el menú principal.

---
*Desarrollado para el Hackathon de 32 KB.*
