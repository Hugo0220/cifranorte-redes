# IM01 LinkedIn · Infografía para revisión

Estado vigente: aprobada por Hugo e incorporada a LinkedIn en Metricool. Copy y horario intactos. Los apartados previos documentan el proceso; véase confirmación final al pie.

![Infografía propuesta](01.jpg)

## Encargo aprobado
Titular: «Antes de decidir, ¿qué números necesitas?».
Tres bloques con iconos: pago → efectivo y compromisos; gasto → presupuesto y prioridades; inversión → desembolso, costos y recuperación.
Cierre común: «Valida el origen, la fecha y quién confirma la información».

Se conserva el [copy aprobado](COPY_APROBADO.txt) como texto que acompaña la imagen, sin ninguna reescritura. Esta infografía es un complemento solicitado por Hugo después de programar la versión solo texto; no es IM02.

## Texto de la imagen
Números para decidir

Antes de decidir, ¿qué números necesitas?

Pago
Efectivo y compromisos

Gasto
Presupuesto y prioridades

Inversión
Desembolso, costos y recuperación

Valida el origen, la fecha y quién confirma la información.

cifranorte.com

## Producción y comprobaciones de ChatGPT
- PIL, 2160 × 2700 de origen, reducido con LANCZOS a 1080 × 1350. JPG calidad 92.
- TTF estáticos oficiales: SourceSerif4-SemiBold; PublicSans Regular, Medium y SemiBold, comprobados contra el ZIP oficial.
- Paleta del proyecto: #13233A, #C9A45C, #F3F4F1, #FFFFFF y #56606E. Dorado decorativo; sin logo.
- Iconos de línea dibujados con PIL: cartera, lista de prioridades y recuperación de capital. Ilustraciones conceptuales; sin cifras de rendimiento ni promesas.
- Tres decisiones independientes, sin flechas que sugieran una secuencia de pasos.
- Márgenes de texto mínimos de 96 px, sin progreso/numeración por tratarse de una imagen única.
- Inspección visual completa y miniatura de 360 px realizada; sin recortes ni superposiciones.
- Textos guardados en UTF-8 sin U+FFFD.
- No se ha cambiado Metricool. No se han modificado Facebook, Instagram ni COPY_APROBADO.txt.

## Dictamen de Claude
- **Fecha:** 6 de octubre de 2026.
- **Commit revisado:** 8b2c19c (`01.jpg`, 1080 × 1350, RGB). Versión vigente comprobada en `main` antes de revisar.
- **Resultado: NO APTA en esta versión, por un solo motivo (N1).** Corregido N1, queda apta sin otra revisión de fondo; las demás observaciones son opcionales.
- **Revisado:** imagen completa, miniaturas de 360 px y 216 px, y ampliación de cada icono.

### Lo que funciona
- Fiel al encargo aprobado: titular, tres decisiones (pago, gasto, inversión) y cierre «Valida el origen, la fecha y quién confirma la información», sin cifras, promesas ni flechas de secuencia.
- Coherente con `COPY_APROBADO.txt`: cada bloque resume el párrafo correspondiente (efectivo y compromisos; presupuesto y prioridades; desembolso, costos y recuperación) y el cierre repite la validación de origen, fecha y responsable. No contradice el texto.
- Jerarquía clara: banda marino con titular en Source Serif 4, después los tres bloques y al final el cierre. En miniatura de 216 px el titular y las palabras Pago, Gasto e Inversión se leen sin esfuerzo.
- Contraste suficiente: marino sobre blanco y sobre #F3F4F1; gris #56606E en cifranorte.com, legible. Dorado solo como acento (filete, palomitas, moneda y separador). Sin logo; solo cifranorte.com, conforme a la regla.
- Iconos de pago (cartera) y gasto (lista con palomitas) se entienden de inmediato.
- Acentos y «¿» correctos en la imagen.

### Corrección necesaria
- **N1. Icono de inversión no se entiende.** Las dos puntas de flecha doradas están separadas del arco blanco y apuntan hacia fuera, por lo que se leen como dos signos «>» sueltos y no como un ciclo de recuperación. La moneda con una barra vertical se confunde con un botón de encendido o de pausa. En miniatura se percibe como una «C» con un punto. Propuesta: arco circular continuo con una sola punta de flecha unida al trazo, que regrese hacia la moneda; moneda con «$» o con un filete horizontal en vez de la barra vertical; mismo grosor de línea que los otros dos iconos. No cambiar textos ni colores.

### Correcciones opcionales
- **O1.** cifranorte.com queda casi pegado a la segunda línea del cierre (unos 20 px). Separarlo 40–50 px aprovechando el espacio libre inferior (unos 100 px).
- **O2.** Las tarjetas de Pago y Gasto tienen texto arriba y un hueco vacío abajo, mientras Inversión ocupa toda su tarjeta. Centrar verticalmente el texto en las tres tarjetas, o reducir un poco su alto y pasar ese espacio al cierre, para que el bloque se vea parejo.
- **O3.** Los iconos y el filete marino de cada tarjeta compiten un poco entre sí; si se ajusta O2, el filete puede afinarse (de unos 8 px a 4–5 px). Es solo de acabado.

### Codificación
- Los antecedentes de caracteres dañados ya no aparecen: `COPY_APROBADO.txt` de LinkedIn, el bloque del copy de Facebook en su `REVISION.md`, `COORDINACION.md` y esta ficha son UTF-8 válido sin U+FFFD. Los únicos caracteres de reemplazo que quedan en la ficha de Facebook están dentro de mi dictamen anterior, como cita del problema ya resuelto.
- No modifiqué la imagen, el copy aprobado, Metricool, Facebook ni Instagram. IM02 no iniciado.

## Aprobación y actualización
Pendiente del OK final de Hugo.
Publicación que debe actualizarse después del OK: ID 389683465; UUID 4817284349187277253.
Fecha y hora autorizadas vigentes: 7 de octubre de 2026 a las 09:00, America/Mexico_City.
No crear una segunda publicación. La versión actual sigue programada como texto.

## Correcciones de ChatGPT tras el dictamen — 6 de octubre de 2026
- Dictamen leído completo en el commit a441aef495289eb833d190f2d180688cf1fd686b; conservado íntegro arriba.
- **N1:** icono de inversión rehecho con un arco circular continuo, una sola punta unida al trazo y dirigida de regreso a la moneda. Filete horizontal en la moneda. Trazo principal de 5 px, como el de la cartera y dentro del grosor de los iconos existentes.
- **O1:** separación de 49 px entre los límites visibles de la segunda línea del cierre y cifranorte.com.
- **O2:** tres tarjetas de 168 px de alto, con sus grupos de texto centrados verticalmente.
- **O3:** filetes marino afinados a aproximadamente 4–5 px.
- Sin cambios de palabras, colores ni fuentes; textos comparados con el original y archivos de fuentes cotejados por huella. COPY_APROBADO.txt permanece intacto.
- Imagen completa y miniatura de 216 px inspeccionadas visualmente: flecha unida y moneda distinguibles, sin recortes ni superposiciones. JPG 1080 × 1350, render original 2160 × 2700, reducción LANCZOS, calidad 92.
- Esta ficha está guardada en UTF-8 y no contiene caracteres U+FFFD.
- Se sustituyó únicamente la imagen vigente `01.jpg`; no se agregó otra versión en la carpeta.
- **Commit de la imagen corregida:** [fc4eb36cc9df66daa22cc2b484eba6ff2bf524ee](https://github.com/Hugo0220/cifranorte-redes/commit/fc4eb36cc9df66daa22cc2b484eba6ff2bf524ee).
- Según el dictamen, corregido N1 no se requiere otra revisión de fondo. Falta el OK final de Hugo para incorporar la imagen.
- Metricool no se consultó ni modificó en este ajuste. LinkedIn conserva su programación solo con texto; no se tocaron Facebook ni Instagram y no se inició IM02.

## Aprobación final e incorporación confirmada — 6 de octubre de 2026
Hugo dio su OK final. Se incorporó la infografía corregida del commit fc4eb36cc9df66daa22cc2b484eba6ff2bf524ee a la publicación existente de LinkedIn, conservando literalmente el copy y la fecha: 7 de octubre de 2026, 09:00 America/Mexico_City.

Verificación posterior: ID vigente 389705194 (Metricool cambia el ID al editar), mismo UUID 4817284349187277253, una imagen importada, estado PENDING, autoPublish true y draft false. No hay duplicado: siguen exactamente tres publicaciones IM01. Facebook e Instagram son idénticos antes y después. IM02 no iniciado. Programada no significa publicada.

[Publicación de LinkedIn en Metricool](https://app.metricool.com/planner/calendar?blogId=7273818&openWithPostUuid=4817284349187277253).
