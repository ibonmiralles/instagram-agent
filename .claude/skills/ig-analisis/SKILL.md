---
name: ig-analisis
description: Analiza la cuenta de Instagram de Ibon con Metricool (seguidores, alcance, reels top y flojos, audiencia) y escribe un informe en informes/.
---

# Análisis de la cuenta

1. Lee `CLAUDE.md`, `estrategia.md` y el informe más reciente de `informes/` para comparar.
2. Con Metricool (brandId 7871346, Europe/Madrid), pide para el periodo indicado (por defecto, últimos 7 días
   y, para comparar, los 7 anteriores):
   - Evolución: IGEV01, IGEV05, IGEV06, IGEV22, IGEV23, IGEV42, IGEV43, IGEV44.
   - Reels: IGRE01, IGRE03, IGRE06, IGRE23, IGRE11, IGRE10, IGRE07, IGRE12, IGRE21, IGRE24, IGRE30.
   - Posts: IGPO01, IGPO03, IGPO06, IGPO07, IGPO28, IGPO14, IGPO13, IGPO08, IGPO15, IGPO27.
   Metricool devuelve las filas sin nombres de columna: asígnalas en el **mismo orden** en que pediste
   las métricas (p. ej. IGRE10 likes va antes de IGRE07 comentarios). Antes de citar una cifra en el
   informe o el correo, vuelve a comprobar a qué métrica corresponde.
3. Clasifica cada reel en un pilar de `estrategia.md` y calcula por pilar: vistas medias, compartidos,
   guardados, tasa de salto.
4. Escribe `informes/AAAA-MM-DD-analisis.md` con: cifras clave y variación, top 3 y peores 3 con el porqué,
   qué pilar sube o baja y 3 acciones concretas.
5. Si los datos contradicen `estrategia.md`, propón el cambio en el informe (no lo apliques sin decirlo).
