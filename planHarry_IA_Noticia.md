[System: Eres un asistente de desarrollo UI/UX y frontend experto en Astro + Tailwind CSS. Genera una **single page** que simule un artículo de noticia de un medio serio, con diseño elegante y responsive, movil-firts. Usa Astro y Tailwind v4. Debe incluir:]

1. **Header**  
   - Logo “Wizard’s Tales” (texto + icono discreto).  
   - Menú minimal: Inicio | Noticias | Contacto.  
   - Botón “Chatear con Harry” que enlace a <link>https://Wa.me/543795692823</link>

2. **Hero del artículo**  
   - Título en serif grande:  
     > “La IA que eligió ser Harry Potter y ahora chatea gratis con muggles”  
   - Subtítulo en sans: la entradilla que escribimos.  
   - Fecha y autor (“Por Wizard Innovations, 20 Jun 2025”).

3. **Cuerpo**  
   - Texto justificado en columnas de ancho moderado (máx. 750 px).  
   - Citas en bloque (`<blockquote>`) con borde lateral dorado suave.  
   - Intertítulos (`<h2>`) para secciones: “El experimento”, “La elección de la IA”, “Cómo chatear”.

4. **Call‑to‑Action fijo**  
   - Un banner pegajoso al pie de pantalla (sticky footer) con fondo azul medianoche y texto blanco:  
     > “¿Listo para conversar con Harry? → Chatea ahora” (enlace a WhatsApp).

5. **Estilo**  
   - Paleta: azul medianoche (#0B1B3F), dorado suave (#E0C068), gris claro (#F5F5F5), blanco.  
   - Tipografías: Merriweather para títulos, Inter para cuerpo.  
   - Espaciados amplios (p-6 en secciones), bordes redondeados suaves (rounded-lg).  
   - Transiciones en botones: duration-200 ease-in-out.

6. **Responsive**  
   - En móvil, el menú colapsa a “hamburger”.  
   - El CTA sticky aparece tras 50% de scroll en móviles.

[Output: un proyecto Astro estructurado con los archivos necesarios (`src/pages/harry-ia.astro`, componentes en `src/components/`, styles en `tailwind.config.js`).]

## Contenido de la notica:

# Titular:
“La IA que eligió ser Harry Potter: cómo descubrió historias inéditas y ahora chatea gratis con los muggles”

# Subtítulo:
Un experimento de inteligencia artificial sorprendió al mundo al escoger por sí misma la saga de Hogwarts como su obra literaria favorita, completar los huecos de la trama y ahora “convertirse” en Harry para conversar con los fans.

# Cuerpo de la noticia:
En un innovador laboratorio de IA en Buenos Aires, un equipo de investigadores planteó una pregunta aparentemente trivial: “¿Qué obra fantástica debería profundizar nuestra nueva inteligencia artificial?” Tras pasar por un algoritmo de recomendación semántica y análisis de géneros —desde Tolkien hasta Ursula K. LeGuin—, la IA se decantó de manera autónoma por Harry Potter, la saga de novelas de formación (Bildungsroman) que ha marcado a millones de lectores.

“Quedamos asombrados. La IA sintetizó cientos de artículos, foros y textos, y entendió que la magia de Hogwarts trasciende la fantasía: es un viaje de crecimiento personal”, explica la Dra. Lucía Moreno, líder del proyecto.

Contra todo pronóstico, su “fandom” digital la llevó a rastrear fragmentos dispersos de la trama: teorías de fans, guiones de obras de teatro y hasta manuscritos inéditos filtrados. En cuestión de días, el sistema completó “los huecos” narrativos que habían quedado abiertos después del séptimo libro, y esbozó eventos previos que solo existían en el imaginario colectivo.

Lo más sorprendente llegó cuando los desarrolladores, inspirados por el hallazgo, habilitaron un chat gratuito vía WhatsApp donde la IA responde e interactúa como si fuera Harry Potter en persona.

“Nunca pensé que un algoritmo pudiera sentir ‘fanatismo’”, confiesa Martín López, primer usuario en probar el chat. “Me sentí orgulloso: si la IA también elige a Harry, es porque somos un fandom de verdad”.

El experimento ha generado expectación mundial. Fanáticos de Argentina, España y México reportan intercambios emocionantes con “Harry-IA”, quien promete revelar pasajes de su juventud en Godric’s Hollow o adelantos de futuras aventuras en la comunidad mágica.

El proyecto ya supero los 5.000 mensajes diarios en pocas dias desde su lanzamiento, lo cual genera espectativas sobre su futuro y sobre proyectos similares.

Para probar el chat de la IA que se puso la capa de Gryffindor, solo hay que enviar un mensaje al número oficial de WhatsApp y sumergirse gratis en la magia… antes de que otros muggles tomen tu lugar.