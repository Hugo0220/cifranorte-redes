# IM07 · Estado de producción

Fecha de registro: 9 de octubre de 2026. Estado: **producción cerrada y programación verificada el 9 de octubre de 2026**. Claude declaró aptas las tres piezas y Hugo aprobó expresamente los copys, medios y horarios. La versión visual y editorial vigente corresponde al commit `88d56311af54ff129ca51916ecef05db2b645ca6`.

## Versión vigente

- LinkedIn, 21 de octubre: `2026-10-21_linkedin_IM07/COPY.txt` (texto).
- Instagram, 22 de octubre: `2026-10-22_instagram_IM07/COPY.txt` y `01.jpg`–`07.jpg` (carrusel).
- Facebook, 22 de octubre: `2026-10-22_facebook_IM07/COPY.txt` y `01.jpg` (gráfico único + texto).
- Guion editorial y dirección visual: `IM07_Guion_Editorial.md`.
- Primer dictamen: `IM07_Dictamen_Claude_1.md`. LinkedIn apto; Instagram y Facebook requerían correcciones que se aplicaron en esta versión. Los tres COPY.txt no cambiaron.
- Segundo dictamen: `IM07_Dictamen_Claude_2.md`. Claude confirmó apto en los tres canales sobre commit `88d56311af54ff129ca51916ecef05db2b645ca6`, sin bloqueos. Dejó mejoras visuales opcionales.

El Calendario Editorial v0.1 conserva hooks, CTA, formatos, objetivos y fechas. La secuencia añade la pregunta por la causa entre desviación y decisión. No hay cifras, testimonios ni casos reales en estas piezas. Una desviación no se presenta automáticamente como error.

## Revisión de Claude

Primer y segundo dictamen en el [hilo del proyecto](https://claude.ai/code/project/chan_01PSVxPHWpw1gker4ESD36Tn?thread=cmsg_01PSVxPHWpw1gker4ESD36TnTnhx7e4X5FJa4MPwGyHs27), sobre commits `dc7920b08eb2a926b94a66aca038374c3d5bac4e` y `88d56311af54ff129ca51916ecef05db2b645ca6`, respectivamente. Se retiraron logos y códigos internos de las piezas; se añadió `cifranorte.com` a los cierres; se corrigieron numeración, línea de avance y la frase «Compara lo planeado con lo real». Claude verificó visualmente la versión corregida y la declaró apta en los tres canales. Sus mejoras opcionales no bloquearon la aprobación. Hugo aprobó expresamente las tres piezas finales en el chat de producción el 9 de octubre de 2026, después de conocer el dictamen.

## Programación verificada

Hugo aprobó los horarios el 9 de octubre de 2026. Zona horaria: `America/Mexico_City`. Marca Metricool: `cifranorte.mx`, blogId `7273818`.

| Canal | Fecha y hora | ID | UUID | Medio |
|---|---|---:|---:|---|
| [LinkedIn](https://app.metricool.com/planner/calendar?blogId=7273818&openWithPostUuid=-4594667351892343257) | 21 octubre 2026, 11:00 | 392399204 | -4594667351892343257 | Texto |
| [Facebook](https://app.metricool.com/planner/calendar?blogId=7273818&openWithPostUuid=-5458145865759372102) | 22 octubre 2026, 10:00 | 392399517 | -5458145865759372102 | Un JPG |
| [Instagram](https://app.metricool.com/planner/calendar?blogId=7273818&openWithPostUuid=6161988345075420189) | 22 octubre 2026, 18:00 | 392399956 | 6161988345075420189 | Carrusel de siete JPG |

Consulta directa posterior de Metricool: exactamente tres entradas en el rango del 21 al 22 de octubre, una por canal, sin duplicados; las tres en estado `PENDING`, `autoPublish: true` y `draft: false`. Los copys en Metricool coinciden literalmente con los `COPY.txt` vigentes en GitHub, salvo el salto de línea final del archivo. Metricool importó una imagen de Facebook y siete de Instagram en el orden 01–07. Antes de programar se constató una sola versión vigente por pieza, hashes coincidentes entre medios locales y GitHub, y ausencia de duplicados en el rango. Dos intentos de LinkedIn con estructura JSON inválida devolvieron `INVALID_ARGUMENT`; el intento válido creó una sola entrada, confirmada por consulta posterior.

## Traspaso al chat de seguimiento posterior

- Aprobado por Hugo: tres piezas finales y horarios. Dictamen final de Claude: **apto** en los tres canales, sin bloqueos; [hilo de revisión](https://claude.ai/code/project/chan_01PSVxPHWpw1gker4ESD36Tn?thread=cmsg_01PSVxPHWpw1gker4ESD36TnTnhx7e4X5FJa4MPwGyHs27).
- Commit de piezas vigente: `88d56311af54ff129ca51916ecef05db2b645ca6`. Este registro operativo se actualiza en un commit posterior; consultar el historial de GitHub para su SHA.
- Fechas, horas, IDs y UUIDs: tabla anterior. Estado real: **programadas y pendientes de publicación**, no publicadas todavía. Incidencia: dos rechazos de estructura de la solicitud LinkedIn, sin publicación creada; resueltos.
- Pendiente futuro, en el chat único de seguimiento posterior: confirmar publicación efectiva, guardar enlaces públicos y registrar métricas cuando estén disponibles. No iniciar IM08 en este chat.
