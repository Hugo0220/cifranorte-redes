# IM06 · Qué significa establecer una línea base

Estado: producción, revisión, aprobación de Hugo y programación verificadas el 9 de octubre de 2026. Hugo decidió «Sin logo»; las piezas usan `cifranorte.com` solo en su cierre. Segundo dictamen de Claude: **apto en los tres canales**. Las tres publicaciones están programadas; aún no se han publicado.

## Ficha del calendario v0.1

| Canal | Fecha editorial | Formato | Objetivo |
|---|---|---|---|
| LinkedIn | 18 octubre 2026 | Carrusel | Explicar el valor de Mapa sin venta directa |
| Instagram | 19 octubre 2026 | Gráfico único | Fijar concepto |
| Facebook | 20 octubre 2026 | Video corto | Explicar con sencillez |

Pilar: Del diagnóstico a la ejecución. Tesis: antes de medir avance se necesita conocer la situación inicial con indicadores comparables. Horarios aprobados por Hugo: LinkedIn 11:00, Instagram 18:00 y Facebook 10:00, zona `America/Mexico_City`.

## Versión para revisión

- LinkedIn: seis JPG `01.jpg`–`06.jpg`, PDF de seis páginas, `COPY.txt`.
- Instagram: `01.jpg`, `COPY.txt`.
- Facebook: video vertical MP4 de 20 segundos sin audio, vista conjunta y `COPY.txt`.
- Guion, textos exactos, dirección visual y fuentes: [`IM06_Guion_Editorial.md`](IM06_Guion_Editorial.md). El texto visible en cada archivo coincide con el guion.
- Manual vigente: Cifranorte v2.1, octubre 2026. Producción con fuentes y paleta oficiales, sin logotipo por decisión expresa de Hugo.
- Control editorial: sin estadísticas, resultados, testimonios, casos reales ni promesas; el ejemplo de cobranza es solo un indicador.
- QA inicial: seis imágenes LinkedIn y una Instagram a 1080 × 1350; PDF de seis páginas; video H.264 1080 × 1920, 20 s, 12 fps; vistas conjuntas revisadas. El video se entiende sin audio.

## Revisión solicitada a Claude

Revisar las tres piezas y sus copys contra Estrategia Editorial v0.1, Calendario Editorial v0.1, Manual de Identidad v2.1, Método Rumbo e ICP. Identificar solo correcciones necesarias y opcionales, con referencia al archivo y lámina/segundo. Examinar claridad para dueños/directores de pymes, contraste, legibilidad, fidelidad al hook y CTA, definición de línea base como referencia inicial, y comparación con el mismo indicador. No inferir aprobación de Hugo. Registrar dictamen y commit revisado aquí.

### Primer dictamen, 9 de octubre de 2026

Claude revisó el commit `dc1780dbbfbfcb4c5767356437cbbcec3206e5c0` y dictaminó **no apto todavía**: siete ajustes necesarios y una decisión de identidad. Dictamen íntegro: [IM06_Dictamen_Claude.md](IM06_Dictamen_Claude.md). [Hilo de Claude](https://claude.ai/epitaxy/project/chan_01PSVxPHWpw1gker4ESD36Tn?thread=cmsg_01PSVxPHWpw1gker4ESD36TnQ7xTmQXL3cuTcLDrS7eYja).

Aplicado tras el dictamen: portada LinkedIn sin código interno, Mapa contextualizado en la lámina 6, guion alineado con láminas 3–4, Instagram con «mismo indicador», Facebook nombra línea base, mantiene fijo el punto inicial, introduce una segunda marca y explicita «mismo indicador». Copys de publicación intactos.

Hugo eligió la segunda opción: sin logotipo y con `cifranorte.com` en el cierre. Se retiró la marca de todas las láminas y escenas previas y se generaron de nuevo PDF, JPG y MP4.

### Segundo dictamen, 9 de octubre de 2026

Claude revisó el commit de piezas `223749d8a867f2edf6480bb1ece39b8ba12043eb` y dictaminó **apto en LinkedIn, Instagram y Facebook**. Confirmó resueltas las siete correcciones necesarias, la firma sin logotipo, la literalidad de los tres copys y la concordancia PDF/JPG. No identificó bloqueos para la aprobación de Hugo. [Resumen fiel y detalles opcionales](IM06_Dictamen_Claude_2.md). No se modificaron las piezas después de este dictamen.

## Aprobación y programación verificadas

Hugo respondió «Aprobado» el 9 de octubre de 2026 a la propuesta explícita de aprobar las tres piezas, sus copys y los horarios 11:00, 18:00 y 10:00 para los días 18, 19 y 20, respectivamente. Las piezas aprobadas son las del commit `223749d8a867f2edf6480bb1ece39b8ba12043eb`; el registro del segundo dictamen quedó en `ed4c7bcbf1495b5f1db4731a48909ea6e16905cf`. Antes de programar se verificó una sola versión de cada pieza en GitHub, copys sin cambios y ninguna publicación en Metricool del 18 al 20 de octubre.

| Canal | Fecha y hora local | ID | UUID | Medio |
|---|---|---:|---:|---|
| [LinkedIn](https://app.metricool.com/planner/calendar?blogId=7273818&openWithPostUuid=1480111207538838556) | 18 octubre, 11:00 | `392057792` | `1480111207538838556` | PDF de 6 páginas |
| [Instagram](https://app.metricool.com/planner/calendar?blogId=7273818&openWithPostUuid=-4435046230299750948) | 19 octubre, 18:00 | `392057992` | `-4435046230299750948` | JPG único |
| [Facebook](https://app.metricool.com/planner/calendar?blogId=7273818&openWithPostUuid=8151428795460043798) | 20 octubre, 10:00 | `392058117` | `8151428795460043798` | MP4 de 20 segundos |

Verificación independiente tras programar: exactamente tres entradas en Metricool del 18 al 20, una por canal; fechas, horas y red correctas; `PENDING`, `autoPublish: true`, `draft: false`; texto idéntico al `COPY.txt` de GitHub en cada canal; un medio por publicación. Los tres archivos cargados responden con HTTP 200, tipo MIME esperado y longitud idéntica al archivo aprobado (PDF 490728 bytes, JPG 171481 bytes, MP4 229688 bytes). **PENDING significa programada, no publicada.**

## Traspaso breve al chat maestro

- Aprobado: las tres piezas IM06 y sus copys, sin logo y con `cifranorte.com` en el cierre; horarios 18 octubre 11:00 LinkedIn, 19 octubre 18:00 Instagram, 20 octubre 10:00 Facebook (`America/Mexico_City`).
- Commit vigente de piezas: `223749d8a867f2edf6480bb1ece39b8ba12043eb`. Dictamen de Claude: apto en los tres canales, sin bloqueos; [detalle](IM06_Dictamen_Claude_2.md).
- Metricool: LinkedIn `392057792` / `1480111207538838556`; Instagram `392057992` / `-4435046230299750948`; Facebook `392058117` / `8151428795460043798`. Enlaces y horarios en la tabla anterior.
- Estado real: tres publicaciones `PENDING`, autopublicación activa, no borradores, copys y medios verificados, sin duplicados.
- Pendiente futuro: comprobar publicación efectiva en cada fecha y registrar métricas cuando estén disponibles. No inferir resultados antes de tiempo.

IM07 permanece fuera de alcance.
