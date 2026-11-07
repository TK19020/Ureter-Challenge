# URETER CHALLENGE — versión automática

20 preguntas basadas en la guía de uréteres. Cada estudiante abre el mismo enlace, escribe su nombre y juega a su ritmo, sin anfitrión ni código de sala.

## Ejecutar localmente

Instala Node.js 18 o superior. En esta carpeta ejecuta `npm start` y abre `http://localhost:3000`.

## Publicar para compartir el enlace

1. Crea un repositorio de GitHub y sube el contenido de la carpeta `ureter-challenge` (no el ZIP).
2. En Render.com, crea un **Web Service** desde ese repositorio.
3. Usa **Runtime: Node**, **Build Command: `npm install`**, **Start Command: `npm start`**.
4. Cuando Render termine, comparte la URL pública por WhatsApp. Los alumnos solo abren el enlace, ponen su nombre y juegan.

## Notas importantes

- El juego funciona de manera individual y asincrónica. No requiere que alguien presente o avance las preguntas.
- La clasificación compartida existe en la memoria del servidor: **se pierde al reiniciarse o entrar en reposo**. Para un ranking duradero habría que añadir una base de datos.
- Cada alumno tiene 15 segundos por pregunta. El cronómetro sigue corriendo si cambia de pestaña.
- Se permite volver a jugar con el mismo nombre. No hay protección contra múltiples intentos ni validación de identidad.
- En un servicio gratuito, el servidor puede tardar en activarse tras estar inactivo. Pruébalo antes de la clase.
