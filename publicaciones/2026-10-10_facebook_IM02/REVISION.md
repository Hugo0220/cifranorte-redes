# IM02 Facebook — Anticipar necesidades de efectivo

## Estado vigente — 6 de octubre de 2026

- Pieza para revisión: gráfico único `01.jpg` y texto `COPY.txt`. Una sola versión vigente de cada archivo. Fecha editorial del Calendario v0.1: sábado 10 de octubre de 2026; **horario sin aprobar**.
- Idea del gráfico: el saldo de hoy no muestra si un pago vencerá antes de un cobro previsto. La línea temporal «hoy → pago → cobro» plantea revisar el efectivo disponible el día del pago, sin usar fechas ni montos ficticios.
- Adaptación para Facebook: texto directo y conversacional. Explica el posible desfase dentro de una semana que cierra positiva, pide ordenar cobros y pagos por fecha y actualizar con lo real, y termina con una pregunta sobre la frecuencia de revisión.
- Gráfico creado con PIL a 2160 × 2700 y reducido con LANCZOS a JPG 1080 × 1350, calidad 92; fuentes oficiales estáticas Source Serif 4 y Public Sans cotejadas con el ZIP original. Paleta y márgenes laterales de 96 px según protocolo; sin logo, cifranorte.com en el pie. Imagen completa y miniatura revisadas por ChatGPT.
- Verificación directa de Metricool antes de producir: el 10 de octubre solo figura Instagram IM02 a las 09:00. Facebook IM02 **no está programado**. IM01 y las otras adaptaciones IM02 no se modificaron.

## Encargo de revisión para Claude

Revisa `01.jpg` y `COPY.txt` completos. Primero evalúa la precisión financiera: el pago podría vencer antes del cobro, pero solo habría falta de efectivo si el disponible no alcanza ese día; la imagen debe leerse como pregunta, no como afirmación de escasez. Después revisa claridad en miniatura y móvil, jerarquía, contraste, márgenes, uso de las fuentes y paleta, ausencia de logo, coherencia con las adaptaciones aprobadas de IM02 y tono propio de Facebook. Separa correcciones necesarias de mejoras opcionales, señala el lugar o frase exacta y registra aquí el dictamen íntegro con el commit revisado. No modifiques la imagen ni el copy durante la revisión.

## Pendiente

Tras el dictamen de Claude, ChatGPT aplicará las correcciones aprobadas; Hugo revisará el resultado y aprobará, si procede, el texto, gráfico y horario. **No programar en Metricool sin su OK final.**


## Dictamen de Claude — 6 de octubre de 2026
- **Commit revisado:** 635415e9359c7b9d6e5cc9db820f6f8fb4778b56 (versión vigente en `main` al revisar).
- **Resultado: SIN CORRECCIONES NECESARIAS. Listo para aprobación final de Hugo.** Las observaciones de abajo son opcionales.
- **Revisado:** `01.jpg` completo (1080 × 1350, RGB), en miniaturas de 360 px y 180 px de ancho, con muestreo de color en las etiquetas. También `COPY.txt` completo y esta ficha.

### Precisión financiera
- **Imagen:** plantea el riesgo como pregunta («¿Alcanza el efectivo el día del pago?») y no como escasez segura. La línea «HOY → PAGO → COBRO» muestra solo el orden de las fechas, sin montos ni fechas ficticias. Es correcto: un pago anterior al cobro es un riesgo solo si lo disponible no alcanza ese día.
- **Copy:** «Aunque la semana cierre con saldo positivo, podrías no tener efectivo suficiente el día de ese pago.» Usa el condicional y liga el problema a la suficiencia del efectivo ese día, no al simple orden de fechas. «Revisa si alcanza en cada vencimiento» refuerza la misma idea. No hay promesas, cifras ni garantías de cobro.
- **Coherencia con IM02:** usa los mismos términos que LinkedIn e Instagram aprobados: efectivo disponible, cobros previstos, pagos comprometidos y actualizar con lo que realmente ocurrió.

### Lo que funciona
- **Jerarquía:** banda marino con titular en Source Serif 4, después «Mira el orden de las fechas», la línea de tiempo y, al final, la pregunta en caja blanca con filete dorado. Se recorre de arriba abajo sin esfuerzo.
- **Miniatura:** a 360 px de ancho se leen el titular, las tres etiquetas y la pregunta. A 180 px se siguen leyendo el titular y la pregunta, que es lo esencial.
- **Contraste:** blanco sobre #13233A; marino sobre #F3F4F1 y sobre blanco. La etiqueta «PAGO» usa el mismo dorado oscuro (≈ #644A19) ya aceptado en IM02 de LinkedIn para texto pequeño sobre fondo claro. El gris de «HOY» y del dominio es legible.
- **Márgenes:** texto y caja entre x = 96 y x = 984. El dominio está a unos 105 px del borde inferior y la etiqueta superior a más de 96 px del borde superior.
- **Identidad:** paleta y fuentes oficiales, sin logo, con solo cifranorte.com al pie. El dorado se usa como acento (filete, nodo del pago, barra de la caja).
- **Tono de Facebook:** directo y conversacional, en segunda persona, y cierra con una pregunta abierta que invita a comentar. La extensión (≈ 90 palabras) es adecuada.
- **Codificación:** `COPY.txt` y esta ficha son UTF-8 sin U+FFFD.

### 1. Correcciones necesarias
Ninguna.

### 2. Mejoras opcionales
- **O1. Titular de la imagen: «El saldo de hoy no responde por mañana.»** «Responder por» significa «garantizar», así que el sentido es correcto, pero en una lectura rápida puede sonar raro. Más directo, si Hugo lo prefiere: «El saldo de hoy no garantiza el de mañana.» o «El saldo de hoy no te dice qué pasará mañana.».
- **O2. Primera línea del copy: «Ver el saldo de hoy no responde todas las decisiones de mañana.»** Es el gancho del calendario, pero «responder decisiones» es poco natural. Alternativa fiel a la idea: «Ver el saldo de hoy no resuelve todas las decisiones de mañana.». Si se prefiere conservar literal el texto del calendario, puede quedar.
- **O3. Enlace en el copy.** En Facebook los enlaces sí funcionan. Se puede cerrar con «Más en cifranorte.com» o con el enlace al diagnóstico (cifranorte.com/diagnostico/) antes de la pregunta final.
- **O4. Retícula detrás del titular.** Las líneas de la retícula cruzan el titular blanco. No afectan la lectura, pero quitarlas detrás del texto, o dejarlas solo a la derecha, limpiaría la banda.
- **O5. Recorte cuadrado.** Algunas vistas de Facebook (escritorio, compartidos) recortan la imagen a 1:1 centrado. En ese caso se pierden la etiqueta superior y cifranorte.com, pero el titular, la línea de tiempo y la pregunta se conservan. No requiere cambio; solo conviene saberlo.

### 3. Conclusión
**Listo para aprobación final de Hugo.** No hay correcciones necesarias. Las mejoras O1 a O4 son a criterio de Hugo; si aprueba alguna, ChatGPT la aplica y basta una comprobación breve.

No modifiqué la imagen ni el copy, y no programé nada. Este dictamen no sustituye la aprobación de Hugo. Fecha editorial: 10 de octubre de 2026; horario sin aprobar.

## Ajustes de claridad de ChatGPT tras el dictamen — 6 de octubre de 2026

- **O1 aplicada:** el titular de `01.jpg` ahora dice «El saldo de hoy no te dice qué pasará mañana.». Conserva el sentido de que el saldo actual no anticipa los vencimientos futuros; la pregunta sobre suficiencia de efectivo el día del pago y el resto del gráfico siguen iguales.
- **O2 aplicada:** la primera línea de `COPY.txt` ahora dice «Ver el saldo de hoy no basta para tomar las decisiones de mañana.». El resto del copy se conservó literalmente.
- **O3 no aplicada:** el dominio ya aparece en el gráfico. Esta pieza educativa conserva una sola invitación a comentar al final del copy, sin añadir un llamado comercial.
- **O4 no aplicada:** la retícula tenue no perjudica la lectura en la imagen ni en miniatura y mantiene continuidad visual con IM02 LinkedIn.
- **O5:** se toma nota del posible recorte cuadrado; el titular, la línea de tiempo y la pregunta se mantienen en el área central.
- Imagen completa y miniatura de 324 px inspeccionadas tras volver a exportar. Formato 1080 × 1350; fuentes y paleta originales, márgenes de texto ≥ 96 px, sin logo. Ningún otro texto de imagen, elemento gráfico ni párrafo del copy cambió. Archivos de texto UTF-8 sin U+FFFD.
- **Estado:** pendiente una comprobación breve de Claude solo de O1 y O2; después Hugo dará la aprobación final y decidirá el horario. Facebook IM02 sigue sin programar.

## Comprobación breve de Claude (O1 y O2) — 6 de octubre de 2026
- **Commit revisado:** 51175ed563ad652efeccdbc833e797f502451b03.
- **Resultado: O1 y O2 CORRECTOS.** La pieza sigue **lista para aprobación final de Hugo**.
- **O1 (titular de `01.jpg`):** «El saldo de hoy no te dice qué pasará mañana.» Es claro, conversacional y conserva el sentido: el saldo actual no anticipa el desfase entre pagos y cobros. No promete ni afirma que vaya a faltar efectivo; la pregunta «¿Alcanza el efectivo el día del pago?» sigue planteando el riesgo como duda.
  - **Diseño:** tres líneas en Source Serif 4 blanca, dentro de los márgenes (x = 96 a ≈ 700) y dentro de la banda marino. Sin solapes. El resto de la imagen no cambió.
  - **Observación menor:** el rabo de la «p» de «pasará» termina en y ≈ 446 y el filete dorado empieza en y ≈ 463, unos 17 px de separación. No se tocan ni se ve apretado en miniatura; no requiere cambio.
- **O2 (primera frase de `COPY.txt`):** «Ver el saldo de hoy no basta para tomar las decisiones de mañana.» Es natural y correcta, y conserva la idea del gancho del calendario. Además conecta con el titular sin repetirlo. El resto del copy no cambió.
- **Codificación:** `COPY.txt` y esta ficha son UTF-8 sin U+FFFD.
- No modifiqué la imagen ni el copy, y no programé nada. Aprobación final y horario: Hugo.

## Aprobación final y programación confirmada — 6 de octubre de 2026

- Hugo aprobó expresamente el gráfico y copy vigentes de IM02 Facebook y el horario sugerido: sábado 10 de octubre de 2026 a las 18:00, zona America/Mexico_City.
- Verificación directa posterior en Metricool, marca cifranorte.mx: exactamente una publicación Facebook IM02, formato post con un gráfico, 10oct2026 18:00 America/Mexico_City, estado PENDING, publicación automática activa, no borrador. El copy programado coincide literalmente con `COPY.txt`; el medio apunta al `01.jpg` aprobado del commit 51175ed563ad652efeccdbc833e797f502451b03.
- Instagram IM02 permanece programado de forma independiente a las 09:00 del mismo día. IM01 y LinkedIn IM02 no se modificaron ni duplicaron. **Programada no significa publicada**; la publicación efectiva queda pendiente de la fecha.
