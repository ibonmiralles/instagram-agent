---
name: ig-reel
description: Prepara un reel (texto, hashtags, hora) a partir de un vídeo de Ibon y lo deja en Metricool pendiente de su aprobación.
---

# Preparar un reel

1. Necesitas: el vídeo (URL pública o archivo subido) y de qué trata. Si falta algo, pregúntalo.
2. Si es un archivo y pide edición, recorta con ffmpeg a 9:16 (1080x1920), elimina tiempos muertos al inicio
   (el primer segundo tiene que tener acción) y añade el gancho como texto grande. Guarda el resultado en el
   scratchpad, no en el repo.
3. Escribe el texto con la voz de Ibon (ver `CLAUDE.md`), terminado en pregunta, con #newchapter + 3–4 hashtags.
4. Elige la hora con `getBestTimeToPostByNetwork` (franja 20:00–21:30 por defecto) evitando huecos
   ya ocupados (`getScheduledPosts`).
5. Enséñale a Ibon el texto, la hora y el gancho.
6. Crea la publicación con **`createScheduledPostForReview`** (nunca `createScheduledPost`).
   Queda pendiente de su aprobación en Metricool.
