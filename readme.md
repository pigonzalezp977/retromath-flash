# ⚡ RetroMath Flash

**RetroMath Flash** es un juego web educativo e interactivo diseñado para ayudar a los niños en etapa escolar a dominar las tablas de multiplicar mediante el desarrollo de la agilidad mental y la automatización cognitiva.

El objetivo principal del juego es evitar que los niños cuenten con los dedos al someterlos a una suave presión de tiempo, o permitirles estudiar a su propio ritmo mediante su Modo Práctica (Zen).

---

## 🚀 Características Principales

* **Dinamismo Crítico:** Los números de las filas y columnas se generan aleatoriamente y se desordenan en cada partida. Esto obliga al cerebro a calcular la intersección real en lugar de memorizar la posición física en la pantalla.
* **Validación en Tiempo Real:** Las celdas reaccionan inmediatamente (verde para aciertos, rojo suave para errores) tan pronto como el niño escribe su respuesta, acelerando el flujo de juego sin necesidad de presionar la tecla "Enter".
* **Diseño 100% Responsivo (Anti-Scroll):** La interfaz está construida con CSS avanzado (`table-layout: fixed`, fuentes fluidas `calc()`) para garantizar que el juego funcione perfectamente en iPads, Laptops y Monitores sin generar barras de desplazamiento horizontal.

---

## 🎮 Evolución y Mejoras (Historial de Cambios)

A lo largo del desarrollo, se han incorporado las siguientes mejoras para maximizar la diversión y la retención del niño:

1. **Perfiles Personalizados:** Al iniciar, se pregunta si el jugador es niño o niña para adaptar dinámicamente los premios visuales (Princesas/Hadas vs Goleadores/Autobots).
2. **Múltiples Modos de Tiempo:** El jugador tiene el control para elegir el nivel de presión: partidas de **2 Minutos**, **5 Minutos** o **Sin Tiempo** (Modo Práctica/Zen).
3. **Sistema de Sonidos (Web Audio API):** Se agregaron efectos de sonido sintetizados nativamente por el navegador: un "ding" para aciertos, un zumbido suave para errores y una melodía triunfal de 8-bits al pasar de nivel. Incluye botón para encender/apagar el sonido.
4. **Persistencia de Datos (Local Storage):** El juego guarda en el navegador de forma automática:
   - El total de puntos históricos acumulados (Global Score).
   - El récord del mejor tiempo para cada nivel.
   - La configuración de sonido y el perfil de género.
5. **Sistema de Recompensas por Constancia:** 
   - Para ganar el gran premio, el niño debe completar el nivel al 100% **tres veces**.
   - Al lograr las 3 victorias, el niño puede elegir interactivamente su premio sorpresa: **Un Chiste** o el **Resumen de un Cuento Clásico**. Las respuestas se despliegan con una atractiva animación.
6. **Manejo de la Frustración:** Si el niño falla más de 3 veces seguidas enfrentando al reloj, el juego le da un tip amigable para que juegue en el modo "Sin Tiempo" y aprenda a su propio ritmo.
7. **Control Total:** Botón de pausa en pleno juego y opción de "Borrar Progreso" en el menú (con confirmación de seguridad).

---

## 🕹️ Niveles de Dificultad

- **Nivel 1 (Básico):** Cuadrícula de 3x3. Tablas aleatorias del 2 al 5.
- **Nivel 2 (Intermedio):** Cuadrícula de 4x4. Tablas aleatorias del 2 al 9.
- **Nivel 3 (RetroMath Pro):** Cuadrícula de 4x5. Tablas aleatorias del 2 al 12.

---

## 🛠️ Detalles Técnicos

- **Arquitectura:** Desarrollado como un MVP en un único archivo (`index.html` auto-contenido).
- **Tecnologías:** HTML5, CSS3, Vanilla JavaScript.
- **Cero Dependencias:** No requiere descarga de imágenes (usa Emojis), ni pistas de audio (usa Web Audio API), ni conexión a bases de datos (usa `localStorage`).

---

## ⚙️ Cómo jugar

1. Abre el archivo `index.html` en cualquier navegador web moderno (Google Chrome, Safari, Edge, Firefox).
2. ¡Eso es todo! No requiere instalación en servidores locales ni conexión a internet para funcionar.

---
*Creado con ❤️ para facilitar el aprendizaje de las matemáticas.*