---
name: ig-nocturno
description: Rutina nocturna completa del agente - analiza la cuenta y los referentes, actualiza el plan, guarda todo en el repo y deja a Ibon un resumen en Gmail.
---

# Rutina nocturna

Ibon está durmiendo: trabaja solo y no le hagas preguntas. Si algo falla, anótalo en el resumen.

1. Ejecuta los pasos de `/ig-analisis` para el día anterior (y la semana, si hoy es lunes).
2. Ejecuta los pasos de `/ig-competencia`.
3. Ejecuta los pasos de `/ig-plan` para los próximos 7 días, actualizando el plan existente en vez de
   rehacerlo entero.
4. Haz commit de los archivos nuevos en la rama de trabajo con un mensaje como
   "Informe nocturno AAAA-MM-DD" y haz push.
5. **Envía** un correo con Gmail (`send_message` con `to`, `subject` y `body`; no lo dejes como borrador)
   a la propia cuenta de Ibon, con asunto "📲 Instagram · AAAA-MM-DD". Es lo único que se envía: va a
   su propio correo, nunca a terceros. Si el envío falla, crea un borrador con el mismo contenido y explica
   el error al principio. En el cuerpo:
   - Cómo fue ayer (3 cifras: vistas, seguidores ganados, mejor reel).
   - Lo más interesante de los referentes (2 líneas).
   - **Qué grabar hoy** (1–2 reels con gancho y guion corto).
   - A qué hora publicar.
   - 3 comentarios o personas con las que interactuar hoy.
   Cuerpo corto, que se lea en el móvil en 1 minuto.
6. No publiques ni programes nada sin aprobación.
