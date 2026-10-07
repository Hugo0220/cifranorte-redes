# IM03 Facebook — Cobranza: convertir saldos en información para decidir

## Estado — 7 de octubre de 2026
Hugo aprobó el texto del gráfico y el copy antes del diseño. ChatGPT produjo 01.jpg y COPY.txt conservando el contenido literal. Diseño listo para revisión de Claude; aprobación final pendiente. Fecha editorial: 13 de octubre de 2026, horario sin aprobar. No se programó nada.

## Texto aprobado del gráfico
¿Sabes qué saldos requieren atención primero?

Revisa el monto, los días de atraso y la situación de cada cuenta.

cifranorte.com

## Producción y comprobación
- PIL; render 2160 × 2700, reducción LANCZOS a 1080 × 1350, JPG calidad 92.
- Fuentes estáticas oficiales Source Serif 4 SemiBold y Public Sans SemiBold/Regular verificadas contra ZIP original.
- Paleta oficial, sin logo, dominio al pie dentro del margen de 96 px. Texto literal cotejado automáticamente.
- Titular sobre marino y tres tarjetas que distribuyen la frase aprobada, en orden. Billete sin cifras, reloj para días de atraso y diálogo para situación; sin palomitas que sugieran resolución.
- Imagen completa y miniatura 324 × 405 abiertas e inspeccionadas; sin cortes ni solapamientos. Una sola versión vigente.

## Encargo para Claude
Revisa 01.jpg completo y en miniatura y COPY.txt. Comprueba fidelidad al texto aprobado, claridad de la priorización por monto/atraso/situación, interpretación de iconos, jerarquía, legibilidad, márgenes, contraste, identidad y tono para Facebook. Verifica que no se promete cobro ni se confunde compromiso con efectivo recibido.

Registra aquí el dictamen íntegro y el commit revisado, separando necesarias (N) de opcionales (O), con ubicación y propuesta concretas. No modifiques gráfico ni copy ni crees versiones paralelas. Los cambios a textos aprobados requieren autorización de Hugo. ChatGPT produce, Claude revisa y Hugo aprueba.

Subir el encargo no activa la sesión de Claude; el dictamen queda pendiente hasta que se registre. No programar ni publicar. LinkedIn e Instagram IM03 ya aprobados por Hugo; no modificarlos. IM01 e IM02 intactos.


## Dictamen de Claude — 7 de octubre de 2026

- **Commit revisado:** `a9f0623e7f69d01c139858a0c0275480d0494d54`.
- **Archivos revisados:** 01.jpg (1080 × 1350) a tamaño completo y en miniaturas de 324 × 405 y 216 × 270, además de COPY.txt. No se modificaron el gráfico ni el copy y no se creó ninguna versión paralela.

### Resultado

**Sin correcciones necesarias (N). La pieza está lista para la aprobación final de Hugo.** Las mejoras opcionales (O) no la bloquean; las de texto solo se aplican si Hugo las autoriza.

### Evaluación

- **Fidelidad:** el gráfico reproduce literalmente el texto aprobado. «¿Sabes qué saldos requieren atención primero?» va como titular; la frase «Revisa el monto, / los días de atraso / y la situación de cada cuenta.» se reparte en tres tarjetas, en orden y sin cambios. «cifranorte.com» aparece una sola vez, al pie. Sin logo.
- **Claridad de los tres criterios:** cada tarjeta presenta un criterio con su icono y se leen en orden de arriba abajo. Los iconos son los mismos que Hugo aprobó en la lámina 5 de Instagram: billete sin cifras para el monto, reloj para los días de atraso y globo de diálogo para la situación. No hay palomitas que sugieran «resuelto».
- **Jerarquía y legibilidad:** el titular domina sobre la franja marino, las tarjetas forman un segundo nivel claro y el dominio queda en tercer plano. En miniatura de 216 × 270 se leen el titular y las tres tarjetas.
- **Contraste:** blanco sobre marino #13233A y marino sobre blanco, ambos altos. El dominio, #323A47 sobre #F3F4F1, tiene una relación de 10.3:1.
- **Márgenes:** el contenido está dentro de 96 px a ambos lados; sin cortes ni solapamientos.
- **Identidad:** Source Serif 4 en el titular y Public Sans en tarjetas y dominio. Fondos #13233A y #F3F4F1 verificados en píxel; dorado solo como acento (línea bajo el titular, filete de tarjetas y detalles del billete).
- **Copy:** coherente con el gráfico, sin cifras ni promesas de cobro. Menciona el compromiso de pago solo como algo «por confirmar», así que no lo confunde con efectivo recibido. Cierra con «Guárdalo» y una pregunta para comentar, igual que IM02 Facebook. Tono adecuado para Facebook.

### Correcciones necesarias (N)

Ninguna.

### Mejoras opcionales (O)

Diseño (no requieren autorización de texto):

- **O1. Retícula detrás del titular.** Las líneas de la retícula cruzan por detrás de las letras de «¿Sabes qué saldos requieren atención primero?». El contraste es suficiente, pero en pantalla de teléfono añaden ruido al texto principal. Propuesta: bajar la opacidad de la retícula en la zona del texto o dejarla solo bajo la línea dorada, como en la portada de Instagram, donde va debajo del texto.

Texto (solo con autorización de Hugo):

- **O2. Tarjetas que empiezan con minúscula.** Al repartir una sola frase, la segunda y la tercera tarjeta empiezan con «los días…» y «y la situación…». Se entiende, pero visualmente parecen fragmentos. Hay dos opciones; ambas cambian la redacción del gráfico. La primera, a estilo lista: «Monto» / «Días de atraso» / «Situación de cada cuenta», con «Revisa:» como entrada. La segunda: mantener la frase completa en una sola tarjeta y dejar solo los tres iconos en fila.
- **O3. Coherencia de términos en el copy.** Frase: «Considera el monto, los días de atraso y la situación de cada saldo.» El gráfico dice «de cada cuenta». Propuesta: «…y la situación de cada cuenta.» para usar el mismo término en las dos.

### Comprobaciones

- Archivo en UTF-8, sin caracteres dañados (U+FFFD).
- No se programó ni publicó nada. LinkedIn e Instagram IM03, IM01 e IM02 sin cambios.
