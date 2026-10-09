# IM06 · Dictamen de Claude

Revisado: rama `im06`, commit `dc1780d`, 9 de octubre de 2026. Solo revisión: no se modificó ni programó nada.

Referencias cotejadas: Calendario Editorial v0.1 (filas IM06), Manual de Identidad v2.1, Método Rumbo (Fase 2 · Mapa calcula la línea base que se usa después para medir avance) e ICP v0.1 (dueño que busca "medir avances").

**Resultado: no apto todavía.** El fondo es correcto y bien alineado al Método Rumbo; hay 7 correcciones necesarias, casi todas de una línea de texto.

## Lo que ya cumple

- Hooks y CTA literales en los tres canales (piezas y COPY.txt) coinciden con el calendario.
- Línea base explicada como referencia inicial, no como cifra suelta (LinkedIn 02 y 03; caption de Instagram; copy de Facebook).
- Sin cifras, resultados ni casos inventados; la nota de LinkedIn 04 lo aclara.
- Fuentes Source Serif 4 y Public Sans, marino/papel/dorado según manual; formatos y medidas correctos (1080 × 1350; video 1080 × 1920, 20 s, sin audio).

## Decisión de Hugo antes de corregir (logotipo)

Todas las piezas llevan el logotipo en cada lámina/escena y ninguna muestra cifranorte.com. La regla del 6 de octubre era "sin logo, solo cifranorte.com en la última lámina", pero IM04 e IM05 se aprobaron con logo en todas. Hugo decide cuál rige; si rige la del 6 de octubre, es corrección necesaria en las 8 piezas.

## LinkedIn · carrusel (2026-10-18_linkedin_IM06)

Necesarias
1. **01.jpg** (pie del titular): quitar "IM06 ·". Es un código interno que el público no entiende; dejar solo "Línea base".
2. **06.jpg** (cuerpo): "En Mapa…" no se entiende sin contexto en la imagen. Proponer: "En el Método Rumbo, la fase Mapa convierte el diagnóstico en una línea base para dar seguimiento."
3. **03.jpg y 04.jpg** vs. guion: el texto visible no coincide con `IM06_Guion_Editorial.md` (03 sustituye "Anota el indicador, el periodo, la fuente y la forma de cálculo." por tarjetas; 04 omite "Si eliges días promedio de cobro,"). El diseño está bien; actualizar el guion para que haya una sola versión vigente, ya que `IM06_ESTADO.md` afirma que coinciden.

Opcionales
- 02.jpg: rotular los dos puntos de la línea ("Hoy" / "Después") y escribir "Después, te permite compararlo con el mismo indicador."
- 03.jpg: "FORMA DE CÁLCULO" queda unos píxeles más abajo que "PERIODO"; alinear.
- 04.jpg: la tarjeta blanca tiene media altura vacía; reducirla o centrar el texto.
- 05.jpg: el cuerpo queda muy pegado a la línea del pie; subirlo un poco.

## Instagram · gráfico único (2026-10-19_instagram_IM06/01.jpg)

Necesaria
4. La idea central del calendario es "Antes / después requiere usar el mismo indicador", y la imagen nunca dice "mismo indicador". Cambiar "Después, compara con el mismo criterio." por "Después, compara el mismo indicador con el mismo criterio."

Opcionales
- El hook queda partido en una etiqueta en mayúsculas ("ANTES DE MEJORAR") bajo otra etiqueta (el pilar). Mejor un solo titular: "Antes de mejorar, mide el punto de partida."
- Rotular los puntos de la línea ("Hoy" / "Después").
- "Guarda esta regla." se lee como pie; darle más peso.
- La fórmula omite "fuente" (LinkedIn la incluye); unificar entre canales.

## Facebook · video (2026-10-20_facebook_IM06)

Necesarias
5. **4–8 s**: el término "línea base" no aparece en pantalla en todo el video y, sin audio, el tema no se nombra. Proponer: "Primero, registra cómo estás hoy: esa es tu línea base."
6. **0–16 s, visual**: el punto dorado se desliza de izquierda a derecha en cada escena; no hay punto inicial fijo ni segunda marca (el guion lo pide en 0–4 s y 12–16 s). Se lee como "avance", no como "comparar contra el inicio". Dejar fijo el punto inicial desde 4 s y, a los 12–16 s, añadir una segunda marca sin valores.
7. **12–16 s**: "Después, mide con el mismo criterio." → "Después, mide el mismo indicador con el mismo criterio." (misma regla que en Instagram).

Opcionales
- 16–20 s: espaciado irregular en "TU SIGUIEN TE PASO" y espacio antes del punto en "comparar ."; revisar el kerning del render.
- 8–12 s: la etiqueta "CÁLCULO" queda más baja que "INDICADOR" y "PERIODO".
- 0–16 s: la palabra "Cifranorte" en Public Sans al pie parece una versión alterna del logotipo; usar el logotipo oficial o nada, según la decisión de arriba.
- Si se cambian textos en pantalla, ajustar `COPY.txt` solo si Hugo lo pide; hoy el copy ya es correcto.

## Copys (los tres COPY.txt)

Sin correcciones necesarias. Hook al inicio y CTA al final, literales; tono "tú", sin promesas. LinkedIn explica bien Mapa dentro del Método Rumbo.

## Siguiente paso

ChatGPT aplica las 7 necesarias (y las opcionales que Hugo elija) y Hugo decide lo del logotipo. Después, una segunda revisión rápida sobre el nuevo commit. IM07 no se tocó.
