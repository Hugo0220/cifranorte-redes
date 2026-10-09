# Seguimiento posterior de publicaciones · Cifranorte

## Alcance vigente
Por instrucción expresa de Hugo del 9 de octubre de 2026, el chat único de seguimiento posterior cubre IM01 en adelante. Los chats de producción terminan al aprobar y programar cada IM. No modificar piezas aprobadas, crear duplicados, iniciar ideas madre. No se creó otra automatización.

Antes de actualizar estados, cotejar main, COORDINACION.md y las fichas o estados de cada IM. Confirmar publicación efectiva con evidencia positiva y conservar enlace público; desaparecer del planificador no basta. Comparar contenido cuando sea posible. Registrar métricas disponibles con fuente y fecha; valores ausentes no son ceros. Avisar solo por confirmación, falla, diferencia, duplicado, decisión pendiente o cierre; sin cambios relevantes, silencio. Una IM con sus tres publicaciones verificadas pasa a seguimiento de métricas; no cerrar verificaciones pendientes como si fueran métricas.

## Consulta del 9 de octubre de 2026
Zona America/Mexico_City. Revisión iniciada a las 08:13, antes de las 09:00 previstas para IM02 LinkedIn. Base GitHub leída: main en 87c5d704768cf442f91babc13044cd33cbe4f93c; COORDINACION.md, todas las REVISION.md existentes de IM01–IM05, confirmación de programación IM03 y estados IM05/IM06.

Fuentes: Metricool marca 7273818, getScheduledPosts (7–21 octubre) y getAnalyticsDataByMetrics (7 octubre–9 octubre 08:13:42 -06:00), conectores posts LinkedIn, Instagram y Facebook. Aunque la descripción de getScheduledPosts dice que solo devuelve programadas, esta respuesta incluyó tres registros con provider PUBLISHED y publicUrl: se registra el estado positivo devuelto, no una inferencia por desaparición.

| IM | LinkedIn | Instagram | Facebook | Publicación efectiva | Enlaces públicos | Métricas | Pendientes |
|---|---|---|---|---|---|---|---|
| IM01 | PUBLISHED; previsto 7 oct 09:00 | PUBLISHED; previsto 8 oct 09:00 | PUBLISHED; previsto 8 oct 18:00; discrepancia de ID/enlace | Tres canales reportados publicados por Metricool y con fila de Analytics; comprobación directa pública no completada | Véase registro de enlaces abajo | Disponibles, detalle abajo | Aclarar Facebook; completar cotejo visual y acceso directo |
| IM02 | PENDING; 9 oct 09:00 | PENDING; 10 oct 09:00 | PENDING; 10 oct 18:00 | No confirmada | No disponibles en la respuesta | No consultadas antes de publicación | Verificar cada salida, enlace y contenido |
| IM03 | PENDING; 11 oct 11:00 | PENDING; 12 oct 18:00 | PENDING; 13 oct 10:00 | No confirmada | No disponibles en la respuesta | No consultadas antes de publicación | Verificar cada salida, enlace y contenido |
| IM04 | PENDING; 14 oct 11:00 | PENDING; 15 oct 18:00 | PENDING; 15 oct 10:00 | No confirmada | No disponibles en la respuesta | No consultadas antes de publicación | Verificar cada salida, enlace y contenido |
| IM05 | PENDING; 16 oct 11:00 | PENDING; 17 oct 18:00 | PENDING; 17 oct 10:00 | No confirmada | No disponibles en la respuesta | No consultadas antes de publicación | Verificar cada salida, enlace y contenido |
| IM06 | PENDING; 18 oct 11:00 | PENDING; 19 oct 18:00 | PENDING; 20 oct 10:00 | No confirmada | No disponibles en la respuesta | No consultadas antes de publicación | Verificar cada salida, enlace y contenido |

Los 15 registros IM02–IM06 tienen autoPublish true y draft false; IDs y horarios coinciden con las fuentes operativas. Una entrada por canal e IM en la respuesta del rango consultado. Esto no excluye duplicados fuera de esa fuente o rango.

## IM01 · Enlaces y comprobaciones
- LinkedIn: https://www.linkedin.com/feed/update/urn:li:share:7513615331349815296 · ID Metricool 389705194, UUID 4817284349187277253. ID público urn:li:share:7513615331349815296 coincidente entre planificador y Analytics. Copy Analytics idéntico a COPY_APROBADO.txt en main, ignorando únicamente el salto final del archivo. Imagen publicada pendiente de cotejo visual.
- Instagram: https://www.instagram.com/p/DePNstUDHHd/ · ID Metricool 389611224, UUID 8316108970299376752. Enlace coincidente entre planificador y Analytics. Copy de Analytics idéntico al registro publicado del planificador; no existe REVISION.md ni COPY.txt de Instagram IM01 en el árbol consultado, por lo que no se acredita cotejo literal contra un archivo aprobado de GitHub. Siete medios en el registro; cotejo visual publicado pendiente.
- Facebook, planificador: https://facebook.com/122106698031495449/posts/122109304947495449 · ID Metricool 389683759, UUID 1307319234200882002, provider id 122109304947495449.
- Facebook, Analytics: https://facebook.com/122106698031495449/posts/122109304983495449 · postId 1380566705144559_122109304983495449. Copy idéntico al registro publicado del planificador y al bloque de copy de REVISION.md. Los sufijos públicos 122109304947495449 y 122109304983495449 difieren. No se elige un enlace canónico ni se declara duplicado sin comprobar ambos.
- Intentos de lectura pública directa de los cuatro enlaces mediante búsqueda web: DisabledError. No se observó directamente el contenido en las redes. No equivale a enlace roto o publicación fallida.
- Acción recomendada: abrir ambos enlaces Facebook en la página de Cifranorte/Metricool, comprobar si corresponden a la misma publicación o a dos distintas, y conservar el enlace canónico. No borrar ni reprogramar por esta discrepancia.

## IM01 · Métricas observadas
Fuente Metricool Analytics, consulta 9 octubre 2026, en la revisión iniciada a las 08:13 America/Mexico_City. Las fechas compactas se conservan como devuelve la fuente, sin inferir zona horaria.
- LinkedIn: created 20261007150451; impresiones 25; clics 2. Comentarios, reacciones y compartidos null: no disponibles.
- Instagram: timestamp 20261008150453; comentarios 1; me gusta 1; alcance 1; guardados 0; vistas 3. Compartidos null: no disponible.
- Facebook: created 20261009000147; impresiones 4; alcance 1; comentarios 0; reacciones 0; compartidos 0. Estas métricas corresponden exclusivamente al enlace de Analytics terminado en 122109304983495449; no atribuirlas al otro ID ni sumarlas como duplicado.
- Sin estimaciones, conversiones, métricas agregadas entre redes ni sustitución de null por 0.

IM01 no queda cerrada con únicamente métricas pendientes: falta resolver la identidad Facebook y el cotejo directo/visual. No se detectó falla explícita en los estados recibidos.

## Traspaso IM07 integrado — 9 octubre 2026, 15:24 America/Mexico_City

Fuente operativa cotejada en main: commit `ee27684cfd11baca09570fd4862cd7b2ae461afd`, COORDINACION.md y [IM07_ESTADO.md](IM07_ESTADO.md). Producción cerrada, dictamen final de Claude apto y aprobación de Hugo registrados. Versión aprobada de piezas: `88d56311af54ff129ca51916ecef05db2b645ca6`.

| IM | LinkedIn | Instagram | Facebook | Publicación efectiva | Enlaces públicos | Métricas | Pendientes |
|---|---|---|---|---|---|---|---|
| IM07 | PENDING; 21 oct 2026 11:00 | PENDING; 22 oct 2026 18:00 | PENDING; 22 oct 2026 10:00 | No confirmada; fechas futuras | Pendientes; los enlaces del planificador no son enlaces públicos | Pendientes de publicación y disponibilidad | Confirmar cada salida, guardar enlace público, cotejar contenido aprobado y después registrar métricas con fuente y fecha |

Marca Metricool 7273818; zona America/Mexico_City. IDs / UUIDs registrados en la fuente:
- LinkedIn: 392399204 / -4594667351892343257; texto.
- Facebook: 392399517 / -5458145865759372102; un JPG.
- Instagram: 392399956 / 6161988345075420189; siete JPG en orden 01–07.

La ficha documenta una consulta directa de Metricool del 9 de octubre: tres entradas PENDING, autoPublish true, draft false, copys exactos y una entrada por canal. Este traspaso se basa en ese registro; no representa una nueva consulta a Metricool ni publicación efectiva. Los dos rechazos de estructura LinkedIn constan como resueltos sin crear entradas; no se reabren.

IM07 se incorpora exclusivamente al seguimiento posterior. Sin nuevas piezas, nuevos chats de producción, cambios de programación, duplicados ni nueva automatización. No iniciar IM08 ni otras ideas madre desde este chat. Las restricciones históricas de «no iniciar IM07» significan no producirla aquí; no bloquean recibir su traspaso autorizado.

## Automatización general autorizada — 9 octubre 2026, 15:45 America/Mexico_City

Hugo autorizó una única automatización general de seguimiento desde IM01 en adelante. Esta autorización sustituye las restricciones históricas de no crear seguimiento/automatización.
- Nombre: Seguimiento de publicaciones Cifranorte.
- Referencia administrativa: `6ac96091ff9c8191adf3801dccbf7487`.
- Activa en el chat único de seguimiento; frecuencia diaria a las 10:00, 12:00 y 19:00 America/Mexico_City; primera ejecución prevista 9 octubre 19:00. Lógica condition_watch.
- Alcance inicial IM01–IM07; incorporar automáticamente futuras IM cerradas y programadas según main. Sin tareas por IM.
- Consultar solo canales vencidos pendientes y novedades; capturas de métricas aproximadamente a 24 horas y 7 días cuando estén disponibles, evitando lecturas repetitivas.
- Avisos solo ante nuevo hito de publicación, incidencia nueva/cambiada, decisión de Hugo o métricas nuevas útiles registradas. Sin cambios relevantes o métricas útiles, silencio. Evitar repetir avisos conocidos.
- Fuentes GitHub y Metricool verificadas con lecturas satisfactorias antes de crear. Inventario de automatizaciones revisado: ninguna otra tarea activa de este propósito; una sola general activa después de la creación.
- No modifica ni duplica piezas o programación y no inicia producción. Estado de publicaciones previo no se actualiza por haber creado la tarea.

## Traspaso IM08 integrado — 9 octubre 2026

Fuente operativa vigente: [IM08_REVISION.md](IM08_REVISION.md), PR #2 fusionado en `main` mediante commit `02b43a17d6ec649448f886e1d58008d1e75e4e2f`. Claude declaró aptas las tres piezas y Hugo aprobó las piezas y horarios finales. Versión visual/editorial aprobada: commit `c74f11606116f988d4b83ea111f04e3a609f4dcf`.

| IM | LinkedIn | Instagram | Facebook | Publicación efectiva | Enlaces públicos | Métricas | Pendientes |
|---|---|---|---|---|---|---|---|
| IM08 | PENDING; 23 oct 2026 11:00 | PENDING; 24 oct 2026 20:00 | PENDING; 24 oct 2026 10:00 | No confirmada; fechas futuras | Pendientes; los enlaces del planificador no son enlaces públicos | Pendientes de publicación y disponibilidad | Confirmar cada salida, guardar enlace público, cotejar contenido aprobado y después registrar métricas con fuente y fecha |

Marca Metricool 7273818; zona `America/Mexico_City`. IDs / UUIDs:
- LinkedIn: `392456676` / `-8621355967532281899`; PDF.
- Facebook: `392455739` / `3153868351232101553`; un JPG.
- Instagram: `392466113` / `-8680810190881274646`; MP4 de 26 s.

La ficha vigente documenta exactamente tres entradas, una por canal, en estado `PENDING`, `autoPublish: true`, `draft: false`, con copys cotejados contra GitHub y sin duplicados. La hora final de Instagram, 20:00, fue elegida bajo delegación expresa de Hugo tras la incidencia técnica registrada. Programadas no significa publicadas.

IM08 queda incorporada exclusivamente al seguimiento posterior. No modificar las piezas aprobadas, no duplicar la programación y no iniciar IM09 desde este chat.
