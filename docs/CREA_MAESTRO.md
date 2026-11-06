# CREA Contenidos: documento maestro para el sitio web

Versión 1.0 · 6 de noviembre de 2026 · Perote, Veracruz
Destino: proyecto web en Claude Code (repo `TCYTO47/crea-contenidos-web.`)

## 0. Cómo usar este documento (leer primero)

Este documento existe para que el sitio se construya con hechos y no con suposiciones.

**Regla 1. Solo hechos de este documento.** Si algo no aparece aquí, no se inventa. Se deja un marcador visible `[POR CONFIRMAR]` en el código o se omite la sección.

**Regla 2. Cada dato tiene estado.**
- **CONFIRMADO**: consta en los documentos de Emmanuel (dossiers, documento maestro, capturas de Meta/TikTok).
- **POR CONFIRMAR**: hay evidencia contradictoria o falta fuente. No publicar tal cual.
- **NO USAR**: Emmanuel lo descartó o está en conflicto.

**Regla 3. Cifras.** Solo se publican cifras con plataforma, periodo y fuente al lado. Nunca comparar a CREA contra otras páginas por nombre. Nunca usar multiplicadores ("23x", "40 a 60 veces", "20x más"). Tono: poderoso y profesional, sin presumir.

**Regla 4. Nombres de marcas y personas de terceros** solo se muestran si hay permiso. Ver sección 9.

**Regla 5. Lenguaje.** Español de México. Gentilicio siempre **"peroteño"**, jamás "perotense". Sin rayas largas (—) en los textos. Escribir "Wiki Wiki" solo después de resolver el nombre (ver sección 12).

---

## 1. Quiénes somos (CONFIRMADO)

- **Nombre:** CREA Contenidos. Razón social: CREA Contenidos, S.C.
- **Qué es:** estudio de producción audiovisual y medio digital de Perote, Veracruz. Meta de Emmanuel: ser *el medio digital de Perote*, el más confiable y editorialmente serio de la región del Cofre de Perote.
- **Director General:** Emmanuel Reyes Zapata.
- **Dirección Creativa:** Joseandy Arroyo Sánchez (también asesor externo de residencias profesionales del ITSPe).
- **Historia:** nace de **PeroTV, El Canal del Valle**, descrito en el dossier de Tercer Tiempo como el primer programa de televisión de Perote, con más de 20 años de antigüedad. La experiencia de entonces evolucionó hasta CREA Contenidos. (Cronología exacta de PeroTV / Canal del Valle: POR CONFIRMAR; el documento maestro la ubica hacia 2005 a 2007.)
- **Sede:** Justo Sierra No. 11, Col. Amado Nervo, Perote, Veracruz, C. P. 91274. El estudio comparte espacio con POP Gastropub.
- **Contacto público (tomado del dossier de Tercer Tiempo):**
  - WhatsApp: 229 330 4106
  - Correo comercial: comercial@crea-contenidos.com
  - Sitio: crea-contenidos.com
- **Diferenciadores:** memoria comunitaria, calidad de producción de estudio, más de dos décadas de capital social local de su director.
- **Enfoque editorial:** orgullo y curiosidad por Perote. Nunca demoler la identidad comunitaria. Se distingue entre lo documentado y lo que pertenece a la tradición oral.

### Público del sitio (definido por Emmanuel)
Un solo sitio para (1) el público peroteño, (2) patrocinadores y negocios locales, (3) renta del estudio.

---

## 2. Identidad visual (CONFIRMADO)

### Paleta de CREA
| Uso | Color |
|---|---|
| Azul marino | `#0F1B2D` |
| Rojo | `#CC2936` |
| Verde | `#0A8F6C` |

Tipografía de documentos: **Calibri**. (Para web, usar una alternativa cercana si Calibri no está disponible y dejarlo documentado.)

### Logotipo CREA Contenidos
- Letras "CREA" en grande: la **C es roja**, "REA" en negro con un recorte/superposición parcial característico (la A se ve como triángulo), y debajo la palabra **"contenidos"** en minúsculas, trazo delgado.
- **Regla fija: el logotipo no se modifica.** Ni recolorear libremente, ni estirar, ni redibujar, ni siquiera en proyectos de terceros.
- Variantes existentes: color (C roja + negro), **blanca** sobre fondo oscuro/azul noche, y **carbón**. Para artes institucionales, usar la versión autorizada y cotejar contra el PNG publicado.
- Los archivos finales están en `~/CREA_material/15_identidad_crea` (Emmanuel). El proyecto web debe usar los PNG/SVG que Emmanuel entregue; **no reconstruir el logo en código**.

### Sub-marcas
| Marca | Descripción visual |
|---|---|
| **Tercer Tiempo** | Escudo con alas azul marino, dorado y rojo, con balones de futbol, basquetbol y beisbol; texto "TERCER TIEMPO" en blanco. Logo propio, cargado en Canva. |
| **PICATREND** ("Tiene su cuento.") | Carita guiñando en coral/naranja + palabra "picatrend" en negro, sobre fondo crema o negro. |
| **5 Siglos Perote** | Insignia conmemorativa en negro: número 5 con soldado y lanza, texto "SIGLOS PEROTE". Se prefiere "5 Siglos" sobre "500 años". |
| **Los Desterrados de Piedra** | Cartel: dos estatuas de soldados en la Fortaleza de San Carlos al atardecer; tipografía serif dorada. |
| **Cuéntame de Perote** | Cortinillas propias en `01_archivo/rubricas_cortinillas`. |

### Sistemas de color por pieza (no mezclar)
- Dossiers de patrocinio de Tercer Tiempo: rosa/crema/azul marino (estilo paletería, solo para ese dossier).
- Dossier Desterrados de Piedra: azul noche, crema y naranja quemado, titulares serif.
- Los Desterrados (audiovisual): dos registros: **Leyenda en azul frío**, **Presente en dorado cálido**.

---

## 3. Programas y líneas editoriales

### 3.1 Cuéntame de Perote · Archivo (CONFIRMADO)
Programa de entrevistas y documentales históricos que da voz a cronistas y expertos. Es el activo insignia y el principal vehículo de patrocinio.
- Episodios mostrados en dossier:
  - *Cuéntame de Perote: El legado del Profesor David Medina Arcos* ("El maestro que Perote no olvida"), 1:02:12.
  - *Cuéntame de Perote: Luis Jorge Oviedo* ("El peroteño del Escuadrón 201", con Laura Oviedo Loranza, hija de Luis Jorge Oviedo Villa), 57:00.
- Otras piezas de Archivo: tributo al Padre Luis Oropeza (*El padre del pueblo*), tributo a Edgar Arroyo Mora, Pedrote, Miguel Rebolledo, Pedro Anzúres.
- **No publicar entrevistas completas ni nombres de entrevistados en el sitio sin autorización** (hay material marcado "revisar autorización").

### 3.2 ¿Ya sabías? (CONFIRMADO)
Videos cortos cinematográficos que contrastan, con rigor, la historia documentada frente a la tradición oral.
| Pieza | Reproducciones en Facebook | Fuente |
|---|---|---|
| El padre del pueblo: Luis Oropeza Rivera | 65,479 | Facebook Meta, CREA, 1 ene a 7 oct 2026, por reel |
| Miguel Rebolledo: el genio oculto del concreto | 48,229 | idem |
| Ferrer y Castells: Los desterrados de piedra | 33,238 | idem |

Notas editoriales: Los Desterrados de Piedra es leyenda cinematográfica de dos soldados españoles del siglo XVIII convertidos en estatuas en la Fortaleza de San Carlos. El dossier señala que la leyenda lleva el origen del relato al Castell de Sant Ferran (Figueres, España, 1793) y que no puede sostenerse como hecho histórico documentado. Se presenta como **leyenda**. Los rostros siempre en silueta o contraluz (decisión narrativa). Patrocinio del episodio Guardianes de Piedra: Tholos Galería.

### 3.3 Tercer Tiempo (CONFIRMADO)
- Programa deportivo en vivo, dedicado al futbol de Perote y sus comunidades. **Facebook, formato horizontal.**
- **Lunes y viernes, 8:00 p. m.**
- **73 min** de duración promedio; **70 episodios** transmitidos en 2026 (según dossier a octubre 2026).
- Conductores: **Pedro Rodríguez Carrillo, Gabriel Escobar, Héctor Landeros.**
- **Don Elmer**: marioneta (adulto mayor, humor mal hablado) con segmento propio, "el cotorreo de Don Elmer".
- **La Voz del Juego**: segmento con María Burgos.
- Narrador deportivo colaborador: Magno López.
- Qué hay en cada episodio: análisis deportivo local, invitados (jugadores, directores técnicos, personajes del deporte regional), Don Elmer.
- Cortes verticales para TikTok y Facebook con plantilla "Shorts Tercer tiempo".
- Transmisiones deportivas especiales: futbol de la Liga Luis Pirata Fuente de Perote, en simultáneo con la página Al Ángulo; basquetbol con vMix.
- Inconsistencia: una captura de Facebook muestra "Tercer Tiempo 74x1" (numeración de emisión) mientras el dossier dice 70 episodios en 2026. **Usar "70 episodios en 2026 (dossier, 7 oct)" y pedir confirmación antes de actualizar.**

### 3.4 Picatrend, "Tiene su cuento." (CONFIRMADO)
Serie de viñetas tipo cómic en carrusel sobre la vida en Perote, para Facebook, Instagram y TikTok. Primer número: "Sobreviviendo a septiembre en Perote". Patrocinan POP Gastropub y Rey Birria Perote. Hay un "Resumen semanal" de seis viñetas (frío, carreteras, Carrera Panamericana, comunidad). Se planea versión en reels con ritmo de lectura de cómic.

### 3.5 Sin prisa (CONFIRMADO)
Cortometraje de Día de Muertos ambientado en la plaza de Perote (título de trabajo "Aquí no hay prisa"). Duración ≈ 100 s. Publicado en Facebook y TikTok el **2 de noviembre de 2026**. Escenarios reales grabados con Meta Ray-Ban y apoyo de varias IA. Personajes: Rosario y Esperanza (reencuentro en la plaza). Existe corte vertical 9:16.

### 3.6 Pana-Pan (CONFIRMADO)
Primera campaña en redes y spot ≈ 28 s para Panadería Pana-Pan (hecho en ≈ 3 horas). Personaje panadero animado. Cliente. **Autorización para caso público: por confirmar.**

### 3.7 Wiki Wiki: programa infantil (EN DESARROLLO)
Show de marionetas en vivo para niños. En el dossier aparece como "Próximamente". Hay tráiler vertical de 41 s y piloto animado de 150 s en `~/CREA_material/05_wiki_wiki`. **Nombre en conflicto** (ver sección 12). En el sitio se anuncia como "próximamente" sin fechas.

### 3.8 Producciones comerciales y Branding House (CONFIRMADO)
Spots, reels y calendarios para marcas locales; servicio de identidad "Branding House" (primer caso: Tholos Galería, símbolo de las dos O). Spot del Día del Padre y Sushi Push para POP Gastropub.

### 3.9 Otros formatos diseñados, NO operando (no presentarlos como existentes)
SEÑAL (noticiero escalable), Perote Vive (programa en vivo), Buenos días Perote (boletín y podcast), videopodcasts, serie animada educativa, K-pop, "Perote 5 Siglos" documental, Simulador de Marca, panel editorial. Estatus real: **POR CONFIRMAR**. En el sitio, a lo más, una sección "próximamente" si Emmanuel lo aprueba.

---

## 4. Métricas verificadas (usar solo así)

Siempre mostrar: cifra, plataforma, periodo, fuente. Tamaño de letra de la fuente legible, no escondida.

### Facebook de CREA, 1 ene a 7 oct 2026 (Meta, Resumen de interacciones)
- 819,702 visualizaciones (+298.7 % vs periodo anterior de 289 días)
- 58,285 interacciones (+411.5 %)
- 73,583 visitas al perfil (+1,121.5 %)
- 72.5 % de las visualizaciones viene de personas que no siguen la página
- 88.1 % de las visualizaciones son reels
- Audiencia: 78.1 % en Perote; 75.6 % entre 25 y 54 años

### Tercer Tiempo, septiembre 2026 (Facebook, datos de Meta, 4 a 28 sep)
- ~75,000 visualizaciones totales (8 episodios: 48,435; transmisión especial final Campeón de Campeones: 14,901; 8 promos: 11,592)
- 77.3 % de las visualizaciones de la página vienen de personas que no siguen a CREA
- Audiencia de Tercer Tiempo (4 sep a 1 oct): 78.4 % en Perote, 75.6 % entre 25 y 54 años
- Tráfico de las transmisiones: 49.7 % feed de Facebook, 24.6 % reels
- La final Campeón de Campeones dejó 31 seguidores netos

### Audiencia ene a abr 2026 (Meta, TikTok Studio e Instagram; dossier Desterrados)
- 74.4 % entre 18 y 44 años (18 a 24: 13.1 %; 25 a 34: 33.1 %; 35 a 44: 28.2 %; 45 a 54: 15.1 %)
- 77.6 % en Perote; 52.5 % hombres / 47.5 % mujeres
- Descubrimiento: 68 % de nuevos espectadores en Facebook; 82.5 % de no seguidores en Instagram; 66 % desde "Para ti" en TikTok

### Seguidores
- Facebook CREA: **2,660 seguidores** al corte del 22 jul 2026 (Meta Business Suite, ventana 25 jun a 22 jul, +650 netos en 28 días). El dossier de Tercer Tiempo (oct 2026) dice "2.1 mil" y un documento interno de ese periodo habla de 3.1 mil. **Mostrar solo la cifra que Emmanuel confirme con captura del día de publicación.**
- TikTok CREA: 1,528 seguidores y 7,689 me gusta (nov 2026, captura de Emmanuel). Piezas que más rinden: Cuéntame de Perote y memoria local (≈ 9 mil a 19.4 mil vistas).

### Escenarios mensuales de Tercer Tiempo (para patrocinadores)
Conservador 40,000; base 60,000; optimista 98,000 visualizaciones/mes. **Deben llevar la leyenda "Estimaciones, no promesas de resultado."** (Es el texto del dossier.)

### Cifras que NO se usan en el sitio
- "23x más seguidores que Al Ángulo", "20x engagement", "4.9x" y cualquier comparación nominal con otras páginas (competidores podrían exhibir cifras mayores).
- "40 a 60 veces" de Archivo (compara reproducciones contra personas alcanzadas; no es una razón válida).
- "56,150" y "73,100" combinados (suman Facebook + TikTok; usar las cifras por plataforma).
- Cualquier cifra sin captura o exportación de respaldo.
- Datos del Simulador de Marca (provisionales, basados en INEGI).

### Regla de actualización
Las cifras caducan. En el código, guardar las métricas en un único archivo de datos (por ejemplo `metrics.json`) con `valor`, `plataforma`, `periodo`, `fuente`, `fecha_de_consulta`, y mostrar siempre estos metadatos.

---

## 5. Oferta comercial para patrocinadores

### Tercer Tiempo (dossier 2026, precios por mes en MXN)
| Paquete | Precio | Incluye |
|---|---|---|
| 1 | $350 | Cintillo en pantalla con logo e información del negocio durante la transmisión |
| 2 | $700 | Video publicitario (provisto por la marca) en las pausas comerciales |
| 3 | $1,000 | Menciones en vivo por los conductores con cintillo, más video grabado por Don Elmer (en el negocio o sobre el negocio) en pausas |

Incluido en todos: reporte mensual de resultados (alcance e interacciones), factura, permanencia del contenido patrocinado en las redes de CREA.

### Archivo / Los Desterrados de Piedra
Patrocinio por marca: **$2,500 a $3,000 MXN por episodio**, según nivel de presencia y exclusividad de categoría. Cupos limitados por episodio. Incluye integración de marca en bloque de patrocinadores y créditos, mención en copy de lanzamiento, difusión pagada segmentada, permanencia junto a un contenido publicado, reporte final y evidencia. Dos niveles: **Patrocinador Presentador** y **Aliado de la Serie**.

### Deportes
Liga Luis Pirata Fuente: referencia histórica de **$1,500 MXN por partido** (cintillo en vivo, mención en Tercer Tiempo el lunes previo y el viernes siguiente). Vigencia: POR CONFIRMAR.

### Criterios comerciales
- Nunca cotizar por debajo del tarifario publicado.
- Instituciones (ITSPe/TecNM): se presenta como **alianza**, canalizada por Vinculación y Comunicación Social, no como compra de publicidad.
- Mensaje central de CREA: no se promete viralidad. Se vende contenido que merece ser visto, estrategia de descubrimiento y medición posterior. Seguidores no es lo mismo que alcance.

### Decisión pendiente para el sitio
¿Se publican precios? Los dossiers los tienen, pero un sitio abierto los expone a la competencia. Recomendación por defecto: **no mostrar precios en el sitio**; mostrar descripción de paquetes y botón "Pide el dossier" (WhatsApp / correo). Confirmar con Emmanuel.

### Paquete Multiplataforma Pyme
Precio y contenido sin definir. **No incluir en el sitio.**

---

## 6. Estudio y producción (CONFIRMADO)

Para la sección "Renta del estudio" y credenciales técnicas:
- **Imagen:** cámaras PTZ, tres cámaras fijas, cámaras Sony mirrorless. (Modelos exactos: POR CONFIRMAR.)
- **Audio:** micrófonos RODE (cuatro con Rodecaster), consola Tascam Mixcast 4, cabina insonorizada, talkback.
- **Mezcla y transmisión:** vMix y OBS, switcher de video, transmisión por Facebook, flujos multicámara NDI, conectividad Starlink.
- **Posproducción:** Final Cut Pro en Mac Mini; Canva.
- **Escenarios:** sets físicos y virtuales, pantalla verde, iluminación, teleprompters.
- **Campo:** Meta Ray-Ban para escenarios reales; laptop con vMix y paquete gráfico para basquetbol.
- **Flujo con IA** (se puede mencionar en general, sin exponer prompts): imágenes con ChatGPT/DALL·E, Leonardo, Nano Banana, Seedream; animación con Hailuo, Google Flow, Runway, HEDRA; voz con ElevenLabs; música con Suno.
- **Tarifas de renta del estudio, talleres y cursos:** no existen definidas. **No inventar precios.** Usar formulario/WhatsApp.
- Honestidad: no hay fotos de "estudio trabajando" en `07_estudio` todavía (solo 3 videos). Usar fotos reales cuando Emmanuel las entregue; no usar imágenes generadas por IA haciéndolas pasar por el estudio.

---

## 7. Clientes, patrocinadores y aliados

### Marcas en el dossier de Tercer Tiempo (12 logos)
POP Gastropub, La Casa del Carpintero, Rey Birria Perote, Roci Terramar, Minimals/Minimal Muebles, Farmacia La Esperanza, Kskrita Deportiva, Eternal Store, Rendillantas, Tholoz Galería, Café Colonial, Liceo Excellens / Instituto Educativo San Carlos.

### Relaciones registradas (documento maestro)
| Cuenta | Relación |
|---|---|
| POP Gastropub | Negocio propio de Emmanuel; patrocinador. Mantener separados los expedientes de ambas operaciones. |
| Tholos Galería (contacto Fernando Ortega) | Cliente y patrocinador; Branding House; Guardianes de Piedra |
| Panadería Pana-Pan | Cliente |
| Dra. Ivonne González | Cliente (brandbook de consultorio dental) |
| Notaría Número 5 de Altotonga | Cliente (calendario FB/IG/LinkedIn) |
| Rey Birria Perote | Patrocinador de Picatrend |
| Al Ángulo / Liga Luis Pirata Fuente | Alianza de transmisión |
| ITSPe / TecNM | Vínculo institucional (residencias con 4 proyectos) |
| Chevrolet | Prospecto. **No mostrar.** |

### Qué se puede mostrar públicamente
Solo logotipos de marcas con **permiso explícito**. Hasta que Emmanuel confirme marca por marca, el sitio debe tener el muro de logos como componente con datos (`clients.json` con campo `autorizado: false` por defecto) y no renderizar los que no estén en `true`.
- Videos propios de cliente disponibles: La Casa del Carpintero, Roci Terramar, Minimal Muebles, Pana-Pan, POP.

### Nombres en conflicto (resolver antes de publicar)
- Tholoz (dossier) vs **Tholos** (rebranding y documento maestro).
- Rey Birria vs "La Pura Birria" (logo adicional enviado).
- Minimals Muebles vs Minimal Muebles.
- Eternal Store: el logo llegó en blanco.
- Farmacia La Esperanza: el logo menciona al Dr. Gabriel Escobar A.; posible coincidencia con un conductor, no confirmada. **No afirmarla.**

---

## 8. Voz y tono del sitio

- Poderosos, potentes, profesionales, intimidantes (en el sentido de seriedad y nivel de producción), sin presumir.
- TikTok se presenta como **escaparate de memoria local**, no como punto débil. No mencionar números pequeños sin contexto.
- Evitar: exceso de emojis, plantillas genéricas de agencia, frases como "líderes en", "número 1" (no hay evidencia), "viral".
- Todo texto público con "peroteño".
- Entrega: listo para usar, sin preguntas innecesarias cuando el contexto alcanza.

---

## 9. Estructura sugerida del sitio (PROPUESTA, para aprobar)

Una sola página principal con anclas más páginas de detalle:
1. **Inicio**: video de fondo o hero con material real (Desterrados, Sin prisa, Tercer Tiempo), promesa en una línea, dos botones: "Ver lo que producimos" y "Anuncia con nosotros".
2. **Programas**: Cuéntame de Perote · Archivo, ¿Ya sabías?, Tercer Tiempo, Picatrend, cortos (Sin prisa), Wiki Wiki ("próximamente").
3. **Cifras** (con fuente y periodo en cada una; ver sección 4).
4. **Patrocina / Anuncia**: Tercer Tiempo y Archivo (sin precios por defecto). Formulario + WhatsApp.
5. **Estudio**: equipo y renta (sin tarifas).
6. **Marcas que confían en nosotros**: muro de logos solo con autorización.
7. **Historia**: PeroTV a CREA.
8. **Contacto**: WhatsApp 229 330 4106, comercial@crea-contenidos.com, dirección.
9. **Aviso editorial**: criterios de verificación (semáforo verde/amarillo/rojo), correcciones visibles.

Requisitos técnicos razonables: responsive móvil primero (la audiencia llega por celular), carga rápida (videos con poster y carga diferida), accesible, fuentes de datos en JSON separados de los componentes, sin dependencias de servicios de terceros sin avisar. Enlaces a Facebook, TikTok e Instagram de CREA: **URLs POR CONFIRMAR** (no están en los documentos).

---

## 10. Reglas editoriales que el sitio debe respetar

- Piezas históricas dejan orgullo y curiosidad, nunca burla ni demolición de la identidad comunitaria.
- Leyenda y presente deben distinguirse visualmente.
- Las afirmaciones llevan fuente: ficha por afirmación (frase, fuente, fecha, semáforo). Fuentes citadas: Sánchez Lamego, *El castillo de San Carlos de Perote* (1971); ficha INAFED (2002) para Pedrote.
- Correcciones públicas y con fecha.
- Contenido generado con IA: las recreaciones se identifican como tales (el dossier ya lo dice: "las imágenes de la leyenda son recreaciones visuales").

---

## 11. Biblioteca de material (carpeta de Emmanuel)

`~/CREA_material` (Mac de Emmanuel; **no está en el repo**). Subcarpetas: 01_archivo (cuéntame de Perote, PeroTV histórico, imagen y sonido del pasado, 5 siglos, rúbricas), 02_tercer_tiempo (125 archivos; 9 episodios largos solo en 360p), 03_cortos (Sin prisa, tráiler, gancho, Desterrados vertical, El padre del pueblo), 04_pana_pan, 05_wiki_wiki, 06_don_elmer, 07_estudio (3 videos), 08_clientes, 08b_pop, 09_metricas (vacía), 10_musica, 11_picatrend, 12_capturas, 13_efectos_sonido, 14_recursos_produccion, 15_identidad_crea.
- Inventario: `_inventario/inventario.csv` (2,019 archivos) y `candidatos.csv` (191 candidatos 1080p+, 5 a 300 s).
- Para el sitio: usar solo piezas 1080p, compresión web (MP4 H.264), con póster. Archivos "revisar_autorización" (Homenaje IA, Taboada, David Medina) **no se publican** hasta aprobación.

---

## 12. Pendientes y conflictos (decisiones de Emmanuel)

| # | Tema | Estado |
|---|---|---|
| 1 | Nombre del programa infantil: Wiki Wiki vs WIKIWIKY vs "Wiki Wikys" vs ¿Quién Anda Ahí? | Resolver antes de publicar |
| 2 | Seguidores de Facebook: 2,660 (jul) vs 2.1 mil (oct) vs 3.1 mil | Confirmar con captura |
| 3 | Número de episodios de Tercer Tiempo (70 en dossier vs 74x1 en captura) | Confirmar |
| 4 | Apellido: Rebolledo Rivadeneira vs Rivadeneyra | Confirmar |
| 5 | Castells vs Catelli/Catells | Usar **Castells** (así lo escribe Emmanuel) |
| 6 | Tholoz vs Tholos | Confirmar escritura del cliente |
| 7 | 500 años de Perote: el dossier Desterrados (ago 2026) dice que la conmemoración "ocurrió en 2025"; el documento maestro la trata como oportunidad futura | Confirmar redacción |
| 8 | ¿Precios visibles en el sitio? | Recomendado: no |
| 9 | Permisos de logos y casos públicos (sección 7) | Pendiente marca por marca |
| 10 | URLs de Facebook, Instagram, TikTok, YouTube de CREA | Faltan |
| 11 | Tarifas de renta del estudio, talleres | No definidas |
| 12 | Paquete Pyme | Sin definir |
| 13 | Datos fiscales/legales de la S.C. | Pendiente (solo si se muestran) |
| 14 | Estatus real de SEÑAL, Perote Vive, Buenos días Perote | Confirmar |

## 13. Lo que NO debe aparecer (descartado por Emmanuel)

- El video del volcán "Yo estaba aquí antes que Perote" **como producción terminada**: solo existe el documento maestro de producción y el brief; el video no está hecho.
- Chevrolet como prospecto.
- Datos personales y proyectos de docencia, video de boda, y otros asuntos ajenos a CREA.
- Logos modificados o reconstruidos.
- Fotos de figuras públicas descargadas de internet.

---

## 14. Fuentes de este documento

1. CREA Contenidos: documento maestro (12 pp., 3 nov 2026), y su versión formal (19 pp.).
2. Referencias visuales de CREA Contenidos (14 pp., 3 nov 2026).
3. Dossier de Patrocinio 2026 de Tercer Tiempo (13 pp.).
4. Dossier de Patrocinio "Ferrer y Castells, Los Desterrados de Piedra" (8 pp., agosto 2026).
5. Capturas de Meta Business Suite y TikTok Studio de Emmanuel (jul y nov 2026).
6. Inventario de `~/CREA_material` (5 a 6 nov 2026).
7. Indicaciones directas de Emmanuel en esta conversación.

Todo lo que no figure en estas fuentes es **POR CONFIRMAR**.
