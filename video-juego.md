# 🦖 Nombre del videojuego que recrearás en tu proyecto
**Dino Game**

---

# 📝 Justificación de por qué eliges dicho videojuego

El **Dino Game** (también conocido como el juego del dinosaurio de Google Chrome) es una excelente opción porque:

- Es **sencillo de implementar**: ideal para practicar fundamentos de programación y desarrollo de videojuegos.
- Requiere lógica básica de **colisiones, físicas simples y puntuación**.
- Puede ampliarse con mejoras: nuevos obstáculos, power-ups, niveles, etc.
- No requiere conexión a internet (¡coherente hasta con su origen! 😅).

---

# 🖼️ Moodboard - Diseño UI imaginado del juego web

 Diseño inspirado en el estilo minimalista del Dino Game original.

![Moodboard Dino Game UI](https://img.poki-cdn.com/cdn-cgi/image/quality=78,width=314,height=314,fit=cover,f=auto/9afd3b92ab41ffca7f368a8fcbd6d39a75894efe0edbc14cf1f067cf625e6678.png)

---

# 📜 Resumen de la historia del juego y recursos multimedia

El **Dino Game** fue creado por el equipo de desarrollo de Google Chrome en 2014. Su propósito original era entretener a los usuarios cuando perdían su conexión a Internet. El protagonista, un **dinosaurio T-Rex**, corre automáticamente a través de un paisaje desértico y debe evitar obstáculos como cactus y aves.

### Curiosidades:
- Su nombre clave durante el desarrollo fue *"Project Bolan"*, en honor a **Marc Bolan**, el líder de la banda T-Rex.
- El juego está **programado en JavaScript** y viene integrado en el navegador Chrome.
- Es jugado por millones de personas, incluso con conexión activa.

### Recursos multimedia:
[🎥 Historia del Dino Game – YouTube](https://youtu.be/iWUU27aORg4)

---

# ⚙️ Algoritmo y mecánicas del juego (lenguaje natural)

## 🔁 Algoritmo General del Juego

1. **Inicio del juego:**
   - Al presionar la barra espaciadora o dar clic en la pantalla, el dinosaurio comienza a correr.

2. **Movimiento del jugador:**
   - El dinosaurio corre automáticamente hacia la derecha.
   - El jugador puede **saltar** (barra espaciadora) o **agacharse** (flecha abajo).

3. **Generación de obstáculos:**
   - Cada ciertos segundos se genera un **cactus** o un **pájaro** a una distancia aleatoria.
   - La velocidad de aparición y desplazamiento de los obstáculos **aumenta con el tiempo**.

4. **Colisiones:**
   - Si el dinosaurio **choca con un obstáculo**, se termina la partida.
   - Se muestra el mensaje **“Game Over”** y la puntuación final.

5. **Puntaje:**
   - Se incrementa **con el tiempo** sobrevivido.
   - Se muestra en la parte superior derecha.

6. **Reinicio:**
   - Al presionar barra espaciadora otra vez, se **reinicia el juego** desde cero.

---

## 🎮 Mecánicas Específicas

- **Saltar**:
  - El dinosaurio puede saltar solo si está en el suelo (no hay doble salto).
  - Se aplica una fuerza hacia arriba y luego la gravedad lo vuelve a bajar.

- **Agacharse**:
  - Se cambia el sprite del dinosaurio a una versión agachada (opcional).
  - Solo sirve para evitar los **pájaros** a baja altura.

- **Dificultad progresiva**:
  - A mayor tiempo jugado, más rápido se mueve el fondo y los obstáculos.

---