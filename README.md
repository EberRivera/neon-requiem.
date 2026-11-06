
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
- Todo el código (HTML, CSS y JS) está en un único archivo `index.html`.

## 📖 Lore: La Anomalía
La simulación está colapsando. Las purgas rutinarias están borrando toda la conciencia digital. Pero una anomalía se niega a ser eliminada: **ZERO**, un humano atrapado dentro del código. 

Ante la aniquilación inminente, la pura fuerza de voluntad y los recuerdos de ZERO se han materializado fuera de su cuerpo físico como una entidad etérea—su alma proyectada como un arma: **WHITE NOISE**. Mientras ZERO dispara para defenderse, WHITE NOISE ejecuta golpes cuerpo a cuerpo y altera la realidad de la simulación. 

Sobrevive a 10 oleadas de antivirus corruptos y enfréntate a la inteligencia central: **THE FIRST**.

## ⌨️ Controles
**Teclado + ratón**
- **W A S D / Flechas:** Mover a ZERO
- **Ratón:** Apuntar · **Clic izquierdo (mantener):** Disparar + golpe de ECHO
- **Rueda del ratón:** Cambiar arma
- **Espacio:** Quantum Shift (intercambia posición con ECHO, 1.1 s de enfriamiento)
- **Q:** Cambia modo (Guard / Assault / Return) y detona OVERRIDE si está listo (8 s)
- **E:** Freeze: congela el tiempo 2 s (enfriamiento 25 s)
- **TAB / C:** Tienda · **1–4:** Compra rápida
- **ESC / P:** Pausa · Menús navegables con flechas + Enter

**Táctil (móvil)**
- Mitad izquierda: joystick de movimiento
- Mitad derecha: apuntar y disparar
- Botones en pantalla: SHIFT, OVR, FRZ, WPN

## 🛒 Tienda (BITS)
Ganas BITS al borrar enemigos (10 normales, 25 Juggernaut, 100 jefe).
| Mejora | Costo |
|---|---|
| Daño +50% (acumulable) | 50 |
| Spread Gun (3 disparos) | 100 |
| Railgun (perfora enemigos) | 200 |
| Reparar +40 HP | 30 |

## ⚡ Power-ups (25% de probabilidad al borrar un enemigo)
- 🟩 **Reparación:** +25 HP
- 🟦 **Overclock:** disparas al doble de velocidad durante 4 s
- 🟪 **Escudo:** invulnerable 4 s

## 👾 Enemigos
- **Grunt:** persigue en enjambre
- **Shooter** (nivel 2+): mantiene la distancia y dispara
- **Hunter** (nivel 4+): carga y embiste
- **Juggernaut** (nivel 6+): tanque con golpe de área
- **Jefe final** (nivel 10): se teletransporta, lanza anillos de 12 balas y, por debajo del 50% de vida, explosiones masivas

## 🔥 Mecánicas
- **Combo:** cada eliminación aumenta el daño hasta x3.5; recibir daño lo reinicia
- **Vínculo:** si ECHO se aleja más de 255 px de ZERO, el vínculo aparece como SEVERED
- **Niveles:** subes un nivel cada 15 eliminaciones; el jefe aparece en el nivel 10
- **Dificultades:** Hard · Nightmare · Hell
- **Récord:** se guarda solo durante la sesión (sin `localStorage`, para no usar almacenamiento del cliente)

## 🎨 Efectos (todo procedural)
Pseudo-3D por capas, scanlines CRT, viñeta, screen shake, hit-stop, partículas,
ondas expansivas, marcas en el suelo, números de daño flotantes y música
generada en tiempo real con la Web Audio API.

## 🌍 Idiomas / Localization
El juego cuenta con un sistema de traducción dinámico e incluye soporte completo en **Inglés** y **Español** directamente desde el menú principal.

