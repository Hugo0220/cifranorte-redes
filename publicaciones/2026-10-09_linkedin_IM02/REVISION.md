# IM02 · LinkedIn · Anticipar necesidades de efectivo

## Estado vigente — 6 de octubre de 2026
- Hugo aprobó el ángulo y los textos de las siete láminas. Después autorizó subir el pie para respetar el margen de 96 px y usar blanco en numeración y tramos anteriores sobre marino; tramo actual dorado.
- Carrusel diseñado por ChatGPT con PIL. Revisión visual propia completada en las siete páginas renderizadas del PDF y en vista conjunta.
- Revisión de Claude: PENDIENTE. No existe dictamen todavía. Guardar esta ficha no activa automáticamente a Claude.
- Aprobación final del diseño por Hugo: PENDIENTE.
- Copy de publicación: producido en COPY.txt, pendiente de revisión de Claude y aprobación final de Hugo. TEXTOS_APROBADOS.txt conserva únicamente las láminas aprobadas.
- Fecha del calendario: 9 de octubre de 2026. Hora: SIN APROBAR. No se programó nada.
- Instagram IM02 (reel corto) y Facebook IM02 (texto + gráfico), previstos para 10 de octubre: pendientes; no producidos en este paso.
- IM01 permanece intacto.

## Archivos vigentes
- [PDF del carrusel](IM02_LinkedIn_Carrusel.pdf), siete páginas, sin texto editable ni OCR.
- [Vista conjunta](IM02_LinkedIn_Vista_Conjunta.jpg).
- 01.jpg a 07.jpg: siete láminas en orden.
- [Textos aprobados](TEXTOS_APROBADOS.txt).
- [Copy de publicación para revisión](COPY.txt).

## Comprobaciones de producción
- JPG final 1080 × 1350, render original 2160 × 2700, reducción LANCZOS, calidad 92.
- PDF 540 × 675 puntos por página: 0.5 puntos por píxel lógico; imagen original a 288 dpi. Siete páginas verificadas, sin capa de texto.
- Fuentes TTF estáticas oficiales SourceSerif4-SemiBold, PublicSans-Regular y PublicSans-SemiBold. Las cuatro fuentes del proyecto se cotejaron byte a byte con el ZIP oficial.
- Paleta e identidad del protocolo. Sin logo; dominio solo en la lámina final.
- Textos cotejados literalmente, permitiendo únicamente saltos de línea y distribución visual. No se recortaron textos aprobados para forzar el objetivo aproximado de 25 palabras.
- Numeración y dominio a y=1227, dentro del margen mínimo de 96 px; blanco sobre marino autorizado.
- Margen de todas las cajas de texto comprobado. Inspección visual sin cortes ni solapes.
- Los iconos de calendario son esquemas, sin fechas, cifras ni resultados inventados.

## Encargo de revisión para Claude
Revisar las siete imágenes y el PDF: fidelidad al texto aprobado, comprensión de la proyección semanal, jerarquía, legibilidad en miniatura, consistencia de iconos, contraste y composición. Identificar el commit revisado. Registrar aquí hallazgos concretos y separar correcciones necesarias de sugerencias.
El copy ya está en COPY.txt. Revisar ahora la pieza completa: PDF, siete imágenes y copy. Comprobar claridad, tono de Cifranorte, coherencia con el calendario y distinción entre cierre semanal y fechas de cobro/pago dentro de la semana. La acción propuesta debe entenderse como revisión de entradas previstas, no como garantía de cobro. No convertir el dictamen en aprobación humana.
No reescribir textos aprobados, producir versiones paralelas, programar ni modificar IM01. Las propuestas de cambio textual requieren aprobación de Hugo.

## Dictamen de Claude
- **Fecha:** 6 de octubre de 2026.
- **Commit revisado:** b2c88061a0b9434519404598f72bba38f96b4ba3 (versión vigente en `main` al revisar).
- **Resultado: REQUIERE AJUSTES (N1, N2 y N3).** N2 y N3 son solo de diseño; N1 es un cambio de texto que necesita la aprobación de Hugo. Hechos esos tres ajustes, la pieza queda lista para aprobación de Hugo sin otra revisión de fondo; lo demás es opcional.
- **Revisado:** `COPY.txt`, `TEXTOS_APROBADOS.txt`, las siete láminas `01.jpg` a `07.jpg` (1080 × 1350), `IM02_LinkedIn_Carrusel.pdf` (7 páginas de 540 × 675 pt; cada página renderizada coincide con su JPG) y `IM02_LinkedIn_Vista_Conjunta.jpg`. Ampliaciones del icono de portada, la fórmula de la lámina 5 y la lista de la lámina 7. Cotejo con el Calendario Editorial v0.1 (viernes 9 de octubre, LinkedIn, carrusel).

### Lo que funciona
- **Fidelidad:** los textos de las siete láminas coinciden literalmente con `TEXTOS_APROBADOS.txt`; solo cambian saltos de línea y distribución.
- **Coherencia con el calendario:** el copy abre con el gancho del calendario («El flujo se vuelve más útil cuando deja de mirar solo lo que ya pasó.») y cierra con su pregunta, ligeramente ampliada. El tema (anticipar necesidades y desviaciones) queda cubierto por las láminas 2 a 6.
- **Copy:** sigue el mismo orden que el carrusel (efectivo disponible, cobros con fecha, pagos con fecha, actualización). No hay cifras, promesas ni garantías. La acción propuesta («identifique la primera fecha en la que los pagos previstos superarían el efectivo disponible y los cobros esperados hasta ese momento») se entiende como revisión de entradas previstas, no como garantía de cobro.
- **Cierre semanal y fechas dentro de la semana:** el copy hace la distinción con precisión («un pago podría vencer antes de que llegue un cobro, aunque el saldo proyectado al cierre de la semana sea positivo»), y la lámina 4 la apoya («Revisa cuáles vencen antes de que lleguen los cobros»). La lámina 3 separa bien venta de efectivo disponible.
- **Tono:** sobrio, práctico, en segunda persona y sin alarmismo. Consistente con Cifranorte.
- **Jerarquía:** etiqueta, titular en Source Serif 4, filete dorado y desarrollo en Public Sans, iguales en las siete láminas. La barra de avance funciona: tramos anteriores en marino (blanco sobre marino en 07) y tramo actual en dorado, como autorizó Hugo.
- **Contraste:** blanco sobre #13233A y marino sobre #F3F4F1, muy por encima de 4.5:1. Folios legibles.
- **Márgenes:** texto entre x = 96 y x = 984. Folio y dominio a y ≈ 1227, con 96 px o más al borde inferior. Sin logo; cifranorte.com solo en la lámina 7.
- **Miniatura:** en la vista conjunta, los siete titulares y los textos principales se leen. Etiquetas y folios quedan muy pequeños, pero son secundarios.
- **Codificación:** `COPY.txt`, `TEXTOS_APROBADOS.txt` y esta ficha son UTF-8 válido, sin U+FFFD.

### 1. Correcciones necesarias
- **N1. Lámina 5 (texto, requiere aprobación de Hugo): la «señal» se define solo con el saldo semanal.** La lámina se llama «La señal / Detecta cuándo no alcanzaría» y la única prueba que da es el saldo proyectado, seguido de «El saldo final de cada semana inicia la siguiente.». Quien lea solo el carrusel puede concluir que si la semana cierra en positivo no hay faltante. Eso contradice la advertencia central del copy, y el carrusel también se comparte sin el copy. Propuesta, agregar al final de la lámina 5 una línea en el mismo estilo que el párrafo final: «Aunque la semana cierre en positivo, revisa si algún pago vence antes de un cobro.». Si se prefiere no sumar texto, alternativa: sustituir «El saldo final de cada semana inicia la siguiente.» por «Revisa el saldo en cada fecha de pago, no solo al cierre de la semana.». La primera opción conserva la idea de arrastre semanal y es la que recomiendo. La flecha decorativa inferior puede retirarse para dar espacio.
- **N2. Lámina 1 (icono de portada).** El círculo dorado con «?» tapa los puntos del tercer calendario: quedan dos puntos sueltos a la izquierda y uno cortado a la derecha, y se ve como un error de dibujo. En la vista conjunta se lee «:(?)». Al ser la portada, es lo primero que se ve en el feed. Propuesta: en el tercer calendario, quitar los puntos y centrar el círculo dentro del cuerpo, o conservar los puntos y colocar el «?» como insignia fuera de la esquina superior derecha. Mismo grosor de trazo. Sin cambiar textos.
- **N3. Lámina 5 (fórmula).** El signo «−» está a la altura de las mayúsculas, por encima del centro de «pagos previstos», y se lee como guion. El «+» sí está centrado. En una lámina de cálculo conviene que el signo sea inequívoco: alinear el «−» al mismo eje vertical y al mismo ancho de trazo que el «+».

### 2. Mejoras opcionales
- **O1. Láminas 2, 3 y 7: cajas con hueco inferior.** El texto queda arriba y la mitad inferior de la caja vacía («Los cobros pendientes van aparte.», «Una venta todavía no cobrada…», «Guárdalo para revisar tu próximo flujo.»). Centrar el texto verticalmente o reducir el alto de la caja. Es el mismo criterio que O2 de IM01.
- **O2. Lámina 4: la lista parte una oración.** Cada tarjeta lleva un fragmento con coma («nómina,», «proveedores,», «impuestos», «y otros compromisos.»), y en formato de lista se lee raro. Opción A, sin tocar texto: dejar «Incluye nómina, proveedores, impuestos y otros compromisos.» como párrafo corrido, sin tarjetas. Opción B, que requiere aprobación de Hugo: tarjetas sin comas ni «y»: «Nómina», «Proveedores», «Impuestos», «Otros compromisos». Recomiendo B por legibilidad.
- **O3. Lámina 7: retícula y numeración.** La retícula de fondo empieza a mitad de la lista y cruza los pasos 2 y 3 pero no el 1. Conviene iniciarla debajo del paso 3 o retirarla de esta lámina. Los números dentro de los círculos (sobre todo el «1») están ligeramente desplazados hacia arriba y a la izquierda. Conviene centrarlos ópticamente.
- **O4. Alineación del folio y aire vertical.** El folio «NN / 07» termina hacia x ≈ 964, mientras cajas, barra y retícula terminan en x = 984; alinearlo a 984. En la lámina 6 hay unos 230 px vacíos entre «Compara lo previsto con lo ocurrido.» y la caja. Repartir ese espacio equilibraría la lámina.
- **O5. Color de las etiquetas sobre fondo claro.** «Punto de partida», «Entradas previstas», etc. usan un dorado oscurecido (≈ #6B5530) que no está en la paleta. Entiendo la razón: #C9A45C sobre #F3F4F1 no alcanza contraste suficiente para texto. Sugiero que Hugo lo acepte como tono derivado del dorado solo para texto pequeño o, si prefiere ceñirse a la paleta, usar marino #13233A con el filete dorado a la izquierda.
- **O6. Copy (requiere aprobación de Hugo), tres ajustes menores:**
  - «Tener efectivo hoy no responde cuánto necesitarás en las próximas semanas.» → «El saldo de hoy no te dice cuánto efectivo necesitarás en las próximas semanas.» (más natural; además conecta con la pregunta final, «saldo de hoy»).
  - «pide a quien lleva tu tesorería» → «pide a quien lleva tus finanzas» (muchas pymes no tienen un área de tesorería).
  - «los cobros esperados hasta ese momento» → «los cobros previstos hasta ese momento» (el carrusel usa siempre «previstos»).

### 3. Conclusión
**Requiere ajustes antes de la aprobación de Hugo.** Hugo debe decidir N1 (texto de la lámina 5) y, si quiere, O2-B y O6. ChatGPT aplica N2 y N3 y los cambios que Hugo apruebe. Hecho eso, la pieza queda lista para aprobación final de Hugo sin otra revisión de fondo.

No modifiqué piezas, textos aprobados, copy, COORDINACION.md ni IM01, y no programé nada. Este dictamen no sustituye la aprobación de Hugo. Fecha prevista 9 de octubre de 2026; horario sin aprobar.

## Decisiones delegadas por Hugo — 6 de octubre de 2026
Hugo pidió a Claude decidir por él en este primer ejercicio («Decide por mí para este primer ejercicio.»). Quedan aprobadas estas decisiones para que ChatGPT las aplique sobre la versión vigente, sin crear versiones paralelas:

- **N1 (aprobado, opción 1):** agregar al final de la lámina 5, en el mismo estilo que el párrafo final: «Aunque la semana cierre en positivo, revisa si algún pago vence antes de un cobro.». Se conserva «El saldo final de cada semana inicia la siguiente.». La flecha decorativa inferior puede retirarse si hace falta espacio.
- **N2 y N3:** aplicar tal como se describen en el dictamen.
- **O1, O3 y O4:** aplicar.
- **O2 (aprobada la opción B):** tarjetas de la lámina 4 sin comas ni «y»: «Nómina», «Proveedores», «Impuestos», «Otros compromisos». Se conserva «Incluye» como encabezado.
- **O5:** se acepta el dorado oscurecido (≈ #6B5530) como tono derivado, solo para etiquetas pequeñas sobre fondo claro.
- **O6 (aprobado completo en COPY.txt):**
  - «Tener efectivo hoy no responde cuánto necesitarás en las próximas semanas.» → «El saldo de hoy no te dice cuánto efectivo necesitarás en las próximas semanas.»
  - «pide a quien lleva tu tesorería» → «pide a quien lleva tus finanzas»
  - «los cobros esperados hasta ese momento» → «los cobros previstos hasta ese momento»
- Actualizar `TEXTOS_APROBADOS.txt` con las láminas 4 y 5 resultantes.
- Después de los ajustes, Claude hace una comprobación breve de N1 a N3, sin otra revisión de fondo. La aprobación final y el horario siguen siendo de Hugo. No programar.
