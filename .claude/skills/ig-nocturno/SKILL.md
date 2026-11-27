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
   el error al principio. En el cuerpo, en este orden:
   - **Hoy es <día>:** qué toca hoy (gancho, guion corto, hora, si va como trial reel).
   - **La semana:** la tabla corta del plan con ✅ / ⏳ / ❌ y lo que falta por hacer.
   - Cómo fue ayer (3 cifras: vistas, seguidores ganados, mejor reel). Si los datos de ayer aún no han
     llegado a Metricool, dilo así, sin suponer que no se publicó.
   - Trial reels que toca revisar hoy, con la recomendación (compartir con seguidores o no).
   - Lo más interesante de los referentes (2 líneas).
   - 3 comentarios o personas con las que interactuar hoy.
   - **Preguntas para ti** (las 2–3 del plan).
   - Los lunes y el día 1 de cada mes, además, la idea del **resto del mes** en 3–4 líneas.
   Cuerpo corto, que se lea en el móvil en 1–2 minutos.
6. No publiques ni programes nada sin aprobación.
