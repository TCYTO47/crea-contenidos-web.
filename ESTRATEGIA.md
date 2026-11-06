# CREA Contenidos · Estrategia del sitio

Archivo que acompaña a `index.html`. Todo lo que aparece aquí está en el código; si cambias una cosa, cámbiala en los dos lugares.

**Cómo se mide el éxito: tres clics.**

| Meta | Clic que se mide | Evento en `dataLayer` |
|---|---|---|
| 1. El peroteño se queda y vuelve | Suscribirse a Buenos días Perote | `newsletter_suscribir` |
| 2. Un negocio pide paquete | Botón "Enviar por WhatsApp" en Anúnciate | `whatsapp_patrocinio` y `whatsapp_patrocinio_paquete` (con el paquete elegido) |
| 3. Una escuela o productor reserva | Botón "Pedir disponibilidad por WhatsApp" en Estudio | `whatsapp_estudio` y `whatsapp_estudio_tipo` |

Los demás botones también envían evento (`hero_*`, `cierre_*`, `whatsapp_fijo`) para saber qué camino lleva a cada clic. Si instalan el Pixel de Meta o Google Analytics, los eventos se envían ahí sin tocar nada más.

---

## 1. Arquitectura

| # | Sección | Ancla | Por qué va aquí |
|---|---|---|---|
| 0 | Encabezado fijo | | Logo, botón rojo "Anúnciate" siempre visible para el dueño de negocio, y menú en fichas que se desliza con el dedo. |
| 1 | Hero | `#inicio` | Quien llega de Facebook decide en 3 segundos. Una frase, un subtítulo, dos botones y la cifra que da confianza. |
| 2 | Ahora | `#ahora` | Responde "¿qué hay hoy?". La tarjeta de Tercer Tiempo calcula sola cuánto falta para la próxima emisión. Es la razón para volver. |
| 3 | Archivo 500 años | `#archivo` | Es el contenido más fuerte (la pieza más vista) y el diferencial de memoria comunitaria. Cierra con el patrocinio por episodio. |
| 4 | Tercer Tiempo | `#tercer-tiempo` | Cita fija dos veces por semana: crea hábito. Puente directo a los paquetes de $350 a $1,000. |
| 5 | Series | `#series` | Muestra el resto del catálogo sin competir con lo anterior. |
| 6 | Newsletter | `#newsletter` | Después de ver todo lo que hay, el paso natural es "avísame". Es el clic 1. |
| 7 | Quién nos ve | `#audiencia` | Cifras reales y marcas que ya patrocinan, justo antes de pedir dinero. Espacios PENDIENTE para testimonios. |
| 8 | Anúnciate | `#anunciate` | Tres pasos hasta WhatsApp con mensaje precargado. Es el clic 2. |
| 9 | Estudio | `#estudio` | Equipo, usos y formulario corto que arma el mensaje de WhatsApp. Es el clic 3. |
| 10 | Nosotros | `#nosotros` | Misión y diferenciales. Va abajo porque el que llega de Facebook quiere contenido primero; el que duda, baja a buscarlo. |
| 11 | Preguntas frecuentes | `#preguntas` | Quita las objeciones de precio, factura y audiencia. También alimenta los datos estructurados de Google. |
| 12 | Cierre | `#cierre` | Los tres clics juntos, uno por tipo de visitante. |
| | WhatsApp fijo | | Siempre abajo en teléfono. Cambia su texto y su mensaje según la sección: en Anúnciate dice "Pregunta por los paquetes", en Estudio "Pregunta por el estudio". |

---

## 2. Hero

- **Etiqueta tipo cintillo de TV:** CREA · Perote, Veracruz
- **Titular:** Perote, contado en serio.
- **Subtítulo:** Noticias, memoria y programas del Cofre de Perote, hechos por peroteños con calidad de estudio.
- **CTA principal (rojo):** Recibe Buenos días Perote → `#newsletter`
- **CTA secundario (borde):** Anuncia tu negocio → `#anunciate`
- **Enlace terciario:** ¿Escuela o productor? Reserva el estudio → `#estudio`
- **Prueba:** 819,702 visualizaciones en Facebook en 2026 · 78.1% de la audiencia está en Perote

Por qué el newsletter es el principal: la mayoría de visitas son audiencia, no anunciantes. El newsletter convierte una visita de Facebook en un regreso. El anunciante tiene el botón rojo fijo del encabezado y el segundo CTA.

"Contado en serio" responde a la competencia sin nombrarla: las páginas informales tienen más seguidores, CREA tiene rigor.

---

## 3. Copia completa por sección

### Ahora · Lo que está pasando
- **Tercer Tiempo, en vivo.** Texto dinámico: "Hoy, 8 pm / Faltan 3 h 20 min", "Mañana, 8 pm", "Lunes, 8 pm" o "En vivo ahora · Al aire desde las 8 pm" (hora del centro de México). Botones: "Qué es Tercer Tiempo" y "Verlo en Facebook" (este último aparece solo cuando se configure la URL).
- **Archivo 500 años · El padre del pueblo.** La pieza más vista de CREA en 2026: 65,479 reproducciones, de la serie documental por los 500 años de Perote. Botón: Ver la serie.
- **Cortometraje · Sin prisa.** Un cortometraje producido por CREA. Botón: Todas las series. (PENDIENTE: sinopsis y estreno.)

### Archivo
Etiqueta: Serie documental · Perote 500 años
> Perote cumple 500 años y su historia tiene nombres propios. Archivo cuenta, pieza por pieza, a las personas y los episodios que hicieron a Perote.

- **El padre del pueblo.** La pieza que más ha visto Perote este año. Sello: 65,479 reproducciones.
- **El ingeniero Rebolledo.** Quién fue y qué tiene que ver con el Perote de hoy.
- **Los Desterrados de Piedra.** Quiénes fueron y de dónde viene el nombre.

Aviso: *Las ilustraciones de Archivo se generaron con inteligencia artificial. Son siluetas y no retratan a personas reales.*

Bloque de patrocinio: **¿Tu marca en la historia de Perote?** Cada episodio de Archivo acepta patrocinadores: de $2,500 a $3,000 por marca por episodio. Botón verde: Patrocinar un episodio (lleva a Anúnciate con ese paquete ya marcado).

### Tercer Tiempo
> El programa en vivo de CREA. Dos noches a la semana para ver, comentar y estar al tanto de Perote en tiempo real.

Horario: Lunes 8 pm · en vivo / Viernes 8 pm · en vivo.
Tarjeta: **Tu negocio en Tercer Tiempo.** Desde $350 al mes tu marca aparece en cada emisión, frente a una audiencia que en su mayoría vive en Perote. Botón: Ver paquetes y precios.

### Series · Más de CREA
> Formatos distintos, mismo cuidado. Del documental al humor, todo se hace aquí.

- **Cuéntame de Perote.** Perote contado por quienes lo viven.
- **Picatrend.** Viñetas sobre la vida en Perote. Si eres de aquí, te vas a reconocer.
- **Don Elmer.** Un personaje de la casa. También aparece en los videos de los patrocinadores de Tercer Tiempo.
- **Sin prisa.** Cortometraje de CREA.
- **Nuevo programa infantil.** Contenido para los más chicos de Perote. Próximamente. Nombre por anunciar. (El nombre Wiki Wiki no se publica hasta que se confirme.)
- **Buenos días Perote.** El newsletter de CREA, directo a tu correo. Suscríbete aquí.

### Newsletter · Buenos días Perote
> Lo importante de Perote en tu correo, para empezar el día sabiendo qué pasa en tu municipio.

Campos: Tu nombre · Tu correo. Botón: Suscribirme gratis.
Nota: Usamos tu correo solo para enviarte Buenos días Perote. Te das de baja cuando quieras.
Confirmación: "Listo, [nombre]. Ya estás en Buenos días Perote."

### Quién nos ve · La audiencia de Perote está aquí
Ver punto 4.

### Anúnciate · Tu negocio, frente a Perote
> Elige un paquete, escribe el nombre de tu negocio y mándanos el mensaje por WhatsApp. Lo demás lo vemos contigo.

**Paso 1. Elige tu paquete**

Tercer Tiempo, precio por mes:
| Paquete | Precio | Nota en la tarjeta |
|---|---|---|
| Cintillo | $350 al mes | Tu marca en pantalla durante el programa. |
| Video en pausa comercial | $700 al mes | Tu video al aire en el corte. |
| Menciones en vivo más video de Don Elmer (sello "Más completo", marcado por defecto) | $1,000 al mes | Incluye reporte mensual y factura. |

Archivo 500 años, precio por episodio:
| Paquete | Precio |
|---|---|
| Patrocinio de Archivo | $2,500 a $3,000 por episodio, por marca |

**Paso 2. Escribe tu negocio.** Campo: Nombre de tu negocio.

**Paso 3. Mándalo por WhatsApp.** Se muestra el mensaje antes de enviarlo:
> Hola CREA. Soy de [negocio] y me interesa el paquete: [paquete] ([precio]). ¿Qué necesitan para empezar?

Botón verde: Enviar por WhatsApp.

Qué pasa después: 1. Te respondemos por el mismo chat. 2. Acordamos fechas y lo que necesitamos de tu marca. 3. Tu negocio sale al aire.

### Estudio · Un estudio de televisión en Perote
> Graba tu podcast, transmite en vivo o lleva a tu grupo a aprender cómo se hace un programa. Equipo profesional sin salir de Perote.

Equipo: Cámaras PTZ y Sony · Micrófonos RODE y Tascam Mixcast 4 · vMix y OBS · Chroma · Teleprompter · Cabina insonorizada y climatizada.

- **Renta del estudio.** Para productores, creadores, negocios e instituciones que necesitan grabar o transmitir con calidad.
- **Talleres para escuelas.** Tus alumnos aprenden a producir en un estudio real, con el equipo que usa CREA.

Formulario: ¿Qué necesitas? (Rentar el estudio / Un taller para mi escuela / Producir un proyecto con CREA) · Tu nombre o el de tu escuela · Fecha (opcional). Botón rojo: Pedir disponibilidad por WhatsApp.
> Hola CREA. Soy [nombre] y me interesa [opción]. Fecha que me interesa: [dd/mm/aaaa]. ¿Me comparten disponibilidad y costo?

### Nosotros · El medio serio del Cofre de Perote
> CREA Contenidos es un medio digital y un estudio de producción audiovisual de Perote, Veracruz. Queremos ser el medio más confiable de la región del Cofre de Perote, y eso se gana con trabajo bien hecho, una publicación a la vez.

- **Memoria comunitaria.** Guardamos y contamos la historia de Perote para que no se pierda. Archivo es la prueba.
- **Calidad de estudio.** Producimos con equipo profesional y lo ponemos al servicio de Perote.
- **Veinte años aquí.** Dos décadas de relación con la gente, los negocios y las escuelas de Perote.

> Cuando un contenido se hace con inteligencia artificial, lo decimos. Siempre.

### Preguntas frecuentes
1. ¿Cuánto cuesta anunciarme en Tercer Tiempo? Por mes: cintillo $350, video en pausa comercial $700, y menciones en vivo más video de Don Elmer $1,000, que incluye reporte mensual y factura.
2. ¿Cuánto cuesta patrocinar Archivo? De $2,500 a $3,000 por marca por episodio.
3. ¿Quién va a ver mi anuncio? Gente de Perote. El 78.1% de nuestra audiencia en Facebook está en Perote y el 75.6% tiene entre 25 y 54 años.
4. ¿Me dan factura? El paquete de menciones en vivo más video de Don Elmer incluye factura y reporte mensual. Para los demás paquetes, pregúntanos por WhatsApp.
5. ¿Cuándo es Tercer Tiempo? Lunes y viernes a las 8 pm, en vivo.
6. ¿Se puede rentar el estudio? Sí, con la lista de equipo. Pide disponibilidad y costo por WhatsApp.
7. ¿Dan talleres a escuelas? Sí. Escríbenos por WhatsApp con el nombre de tu escuela.
8. ¿Cómo recibo Buenos días Perote? Deja tu nombre y tu correo en la sección de newsletter. Es gratis.
9. ¿Usan inteligencia artificial? Cuando un contenido se hace con IA, lleva un aviso que lo dice. Por ejemplo, las ilustraciones de Archivo.

### Cierre
> **Perote tiene mucho que contar. Cuéntalo con nosotros.** Escoge lo que te toca.

Botones: Recibir Buenos días Perote · Anunciar mi negocio · Reservar el estudio.

Pie: CREA Contenidos · Medio digital y estudio de producción audiovisual · Perote, Veracruz. Aviso de transparencia: los textos e ilustraciones de este sitio se elaboraron con apoyo de inteligencia artificial.

---

## 4. Prueba social (solo datos reales)

| Cifra | Texto en el sitio |
|---|---|
| 819,702 | visualizaciones en Facebook en 2026 |
| 78.1% | de la audiencia está en Perote |
| 75.6% | tiene entre 25 y 54 años |
| 88.1% | del contenido visto son reels |
| 65,479 | reproducciones de El padre del pueblo, la pieza más vista |

Fuente citada en el sitio: estadísticas de la página de Facebook de CREA Contenidos, 2026.

Marcas (como texto, sin logos): POP Gastropub, La Casa del Carpintero, Rey Birria, Roci Terramar, Minimals Muebles, Farmacia La Esperanza, Kskrita Deportiva, Eternal Store, Rendillantas, Tholoz Galería, Café Colonial, Liceo Excellens.

Testimonios: tres espacios marcados **PENDIENTE** (patrocinador de Tercer Tiempo, patrocinador de Archivo, escuela o productor del estudio). No hay ningún testimonio inventado.

---

## 5. Código

- Un solo `index.html` con CSS y JS dentro. Sin frameworks. Las imágenes están en `img/`.
- Mobile first: se diseñó a 375 px y crece en 720 y 980 px. Sin scroll horizontal.
- Imágenes WebP (5 a 8 KB cada una) con `loading="lazy"`, `decoding="async"` y medidas fijas para que la página no brinque. El hero no usa imagen: carga al instante.
- Una sola fuente externa (Fraunces, serif para titulares) con `display=swap`; la lectura usa la fuente del sistema.
- Todos los botones miden 52 px de alto (mínimo pedido: 48 px). Verificado con Playwright.
- WhatsApp fijo abajo en teléfono; en escritorio es un botón flotante a la derecha.
- Newsletter en dos campos con validación.
- Accesible: etiquetas en todos los campos, foco visible, respeta "reducir movimiento".
- Configuración en un solo lugar, al inicio del `<script>`:

```js
var CONFIG = {
  whatsapp: "",            // número, ej. 52 + 10 dígitos
  facebook: "",            // URL de la página
  newsletterEndpoint: ""   // URL del servicio de correo
};
```

Mientras estén vacíos el sitio no se rompe: WhatsApp abre con el mensaje listo para elegir contacto, los botones de Facebook no se muestran y el newsletter manda la suscripción por WhatsApp.

---

## 6. SEO local

- **Title:** CREA Contenidos | Noticias Perote, Cofre de Perote y Perote 500 años
- **Description:** Medio digital y estudio de producción de Perote, Veracruz. Noticias Perote, Archivo de los 500 años, Tercer Tiempo en vivo lunes y viernes 8 pm. Anúnciate o renta el estudio.
- **Open Graph:** título "CREA Contenidos | Perote, contado en serio", imagen `img/og-crea.jpg` de 1200 × 630.
- **Geo:** `geo.region` MX-VER, `geo.placename` Perote.
- **Datos estructurados (JSON-LD):** `NewsMediaOrganization` (nombre, descripción, dirección Perote, Veracruz, MX, área servida Perote y región del Cofre de Perote, temas), `WebSite` y `FAQPage` con cuatro preguntas.
- **Términos en encabezados y texto:** noticias Perote, Cofre de Perote, Perote 500 años, peroteños, Perote Veracruz.
- **Por agregar al tener dominio:** `<link rel="canonical">`, `og:url`, URL absoluta en `og:image`, `url`, `logo` y `sameAs` (Facebook) en el JSON-LD. Dar de alta Google Search Console y Perfil de Empresa en Google con la dirección del estudio.

---

## 7. Lo que falta de tu parte para publicar

**Indispensable**
1. Número de WhatsApp de ventas (y si es distinto, el del estudio).
2. URL de la página de Facebook.
3. Servicio de newsletter (Mailchimp, Brevo u otro) y la URL de su formulario.
4. Aviso de privacidad: el sitio pide nombre y correo, la ley mexicana lo exige. Dime la URL o te ayudo a redactarlo.
5. Dominio y hosting.

**Para que la copia quede exacta**
6. Una línea de qué trata Tercer Tiempo y quién lo conduce. Cuánto dura (el contador asume una hora para decir "En vivo ahora").
7. Sinopsis aprobadas de El ingeniero Rebolledo y Los Desterrados de Piedra, y confirmar que El padre del pueblo puede presentarse así.
8. Sinopsis y fecha o lugar de estreno de Sin prisa.
9. Confirmar las descripciones que escribí por inferencia: Cuéntame de Perote ("Perote contado por quienes lo viven"), Don Elmer ("un personaje de la casa"), y qué incluye el cintillo y el video en pausa.
10. Confirmar la lectura de "88.1% son reels" (en el sitio dice "del contenido visto son reels") y la fecha de corte de las cifras de 2026.
11. Confirmar si la factura y el reporte aplican solo al paquete de $1,000 o a todos, y si los precios incluyen IVA.
12. Nombre definitivo del programa infantil.
13. Frecuencia y hora de Buenos días Perote.
14. Confirmar que los "veinte años" se pueden decir como "veinte años aquí" en nombre de CREA.

**Prueba social y materiales**
15. Testimonios reales con nombre, negocio y autorización por escrito (tres espacios PENDIENTE).
16. Logos de las doce marcas patrocinadoras, con permiso para mostrarlos.
17. Fotos reales del estudio para reemplazar la ilustración, y logo de CREA en SVG.
18. Si quieres arte final para Archivo: siluetas y contraluz, sin rostros nítidos, con su aviso de IA si aplica.
19. Pixel de Meta y Google Analytics, para medir los tres clics.
20. Dirección del estudio (para Google y para quien va a rentarlo) y costos de renta y talleres, si quieres publicarlos.

---

## Revisión antes de entregar

- Cifras: 819,702 · 78.1% · 75.6% · 88.1% · 65,479 · $350 · $700 · $1,000 · $2,500 a $3,000. Coinciden con el contexto en sitio, FAQ y JSON-LD.
- Rutas: todos los enlaces internos apuntan a anclas que existen (`#inicio`, `#ahora`, `#archivo`, `#tercer-tiempo`, `#series`, `#newsletter`, `#anunciate`, `#estudio`, `#nosotros`). Los externos son `wa.me` válidos. Los de Facebook están ocultos hasta que exista la URL. Verificado con Playwright: cero anclas rotas, cero errores de consola, cero scroll horizontal a 375 px.
- Voz: sin guiones largos ni rayas, "peroteño" siempre, nunca "perotense". No se menciona a WENCIS. Castells no aparece en el sitio; si se agrega, se escribe así.
- IA: aviso en cada ilustración de Archivo, en la del estudio y en el pie del sitio.
