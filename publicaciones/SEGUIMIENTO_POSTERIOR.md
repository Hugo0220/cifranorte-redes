# Seguimiento posterior de publicaciones · Cifranorte

## Alcance vigente
Por instrucción expresa de Hugo del 9 de octubre de 2026, el chat único de seguimiento posterior cubre IM01 en adelante. Los chats de producción terminan al aprobar y programar cada IM. No modificar piezas aprobadas, crear duplicados, iniciar ideas madre ni iniciar IM07. No se creó otra automatización.

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
