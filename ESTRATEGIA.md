# CREA Contenidos · Notas del sitio (maqueta)

**Fuente única de verdad:** `docs/CREA_MAESTRO.md`. Si algo no está ahí, en el sitio aparece como `[POR CONFIRMAR]` o no aparece.

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | Página única, mobile first. CSS y JS dentro. |
| `data/metrics.json` | **Única fuente de cifras.** Cada una con `valor`, `plataforma`, `periodo`, `fuente`, `fecha_de_consulta`. La página las muestra siempre con esos metadatos. |
| `data/clients.json` | Muro de marcas. Todas con `autorizado: false`. La sección no aparece hasta que al menos una tenga `true` y su `logo`. |
| `docs/CREA_MAESTRO.md` | Documento maestro. |

Las cifras y marcas se cargan con `fetch`. Para verlas en local abre el sitio con un servidor (`python3 -m http.server`), no con doble clic.

## Estructura (sección 9 del maestro)

1. **Inicio:** "Perote, contado en serio." Botones "Ver lo que producimos" y "Anuncia con nosotros". Enlace a renta del estudio. Cifra principal con su fuente. Espacio para video o póster real.
2. **Programas:** Tercer Tiempo (con contador a la próxima emisión, 73 min de duración), Cuéntame de Perote · Archivo, ¿Ya sabías? (tres piezas; Desterrados marcada como **Leyenda** en azul frío, con aviso de recreación), Picatrend, Sin prisa (con aviso de IA), programa infantil (próximamente, sin nombre), producción para marcas.
3. **Cifras:** Facebook de CREA y Tercer Tiempo, desde `metrics.json`.
4. **Patrocina:** principio de "no prometemos viralidad", tres paquetes de Tercer Tiempo y patrocinio de Archivo con sus dos niveles, **sin precios**. Pasos hasta "Pide el dossier" por WhatsApp o correo, con mensaje precargado.
5. **Estudio:** equipo completo de la sección 6, renta y talleres sin tarifas, formulario a WhatsApp.
6. **Marcas:** apagada.
7. **Historia:** PeroTV a CREA, misión, diferenciadores, Director General y Dirección Creativa.
8. **Aviso editorial:** ficha por afirmación, semáforo, fuentes citadas, correcciones con fecha, IA.
9. **Preguntas frecuentes** (sin precios).
10. **Contacto:** WhatsApp 229 330 4106, comercial@crea-contenidos.com, dirección.

WhatsApp fijo abajo, con mensaje según la sección. Eventos para medir: `hero_ver_producciones`, `whatsapp_patrocinio`, `correo_patrocinio`, `whatsapp_estudio`, `whatsapp_contacto` y otros con `data-evento`.

## Decisiones tomadas en esta versión

- **Precios:** no se muestran (recomendación del maestro, sección 5).
- **Buenos días Perote:** retirado por completo. Está en "diseñados, no operando" (3.9).
- **Conductores y colaboradores de Tercer Tiempo:** sin nombres, con marcador, hasta tener permiso (regla 4).
- **Escenarios mensuales (40,000 / 60,000 / 98,000):** no se publican; quedan para el dossier.
- **Porcentajes de crecimiento y seguidores:** no se publican (conflicto de seguidores #2; los crecimientos suenan a presumir).
- **Tipografía:** titulares en serif (Fraunces); lectura en Calibri con Carlito y fuentes del sistema como respaldo.
- **"5 Siglos"** en lugar de "500 años"; no se afirma si la conmemoración ya ocurrió (#7).
- **Logo:** no se reconstruye en código. Hay un marcador donde va el PNG o SVG oficial.
- **Imágenes generadas con IA:** retiradas. Hay marcos `[POR CONFIRMAR]` para pósters y fotos reales.
- **Episodios y entrevistados de Cuéntame de Perote:** no se nombran hasta tener autorización.

## Qué falta para publicar

1. Logo oficial (variante blanca) en PNG o SVG, y arte para compartir de 1200 × 630.
2. Video o póster para el inicio; pósters de las tres piezas de ¿Ya sabías?; fotos reales del estudio. Video en MP4 H.264, 1080p, con póster.
3. URLs de Facebook, Instagram, TikTok y YouTube (`CONFIG.facebook` en `index.html` activa los botones).
4. Permiso para nombrar a conductores y colaboradores de Tercer Tiempo.
5. Lista de episodios y entrevistados de Cuéntame de Perote autorizados.
6. Nombre del programa infantil.
7. Fecha de consulta de cada cifra en `metrics.json` (hoy en `null`).
8. Confirmar 70 episodios vs emisión 74x1.
9. Autorización marca por marca y logos para `clients.json`, y la escritura correcta de Tholos/Tholoz, Rey Birria/La Pura Birria y Minimal/Minimals.
10. Cronología de PeroTV y El Canal del Valle.
11. Definición pública del semáforo editorial y registro de correcciones.
12. Redacción de la conmemoración de 5 Siglos.
13. Aviso de privacidad (el sitio no recoge datos hoy, pero lo necesitarás si agregas formularios con envío).
14. Pixel de Meta o Google Analytics para medir los eventos.
