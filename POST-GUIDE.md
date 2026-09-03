# Guía de posts — ANXiNA

Referencia persistente para redactar posts de [ANXiNA](https://www.anxina.xyz/) a partir de archivos `.txt` y publicarlos en Blogger.

---

## Flujo de trabajo

1. Cada post tiene **su propia carpeta** en la raíz del proyecto (slug descriptivo, sin acentos). Ejemplo: `brasil-electromovilidad-olinia/`.
2. El usuario deja ahí el archivo de información cruda (`.txt` o el nombre que tenga).
3. Se redacta el post en español latinoamericano neutro y se genera el `.html` **en esa misma carpeta**, junto a la info.
4. El usuario pega el HTML en Blogger → editor → vista **HTML**.
5. Se configuran título, etiquetas e imagen destacada con los metadatos entregados.

No mezclar posts: no hay carpeta común de “info” ni de “ready”. `POST-GUIDE.md`, `poll-snippet.html` y `.cursor/` se quedan en la raíz.

---

## Perfil editorial

| Aspecto | Criterio |
|--------|----------|
| Tono | Cercano y conversacional, sin perder credibilidad |
| Extensión | 450–600 palabras (apuntar a ~500). Máximo 650 si el tema trae muchos datos |
| Estructura | Lead corto + 2 o 3 H2. Una caja de datos si aporta. Sin secciones de relleno |
| Español | Latinoamericano neutro: conversacional, sin regionalismos fuertes |
| Uso del .txt | Reescritura completa; no copiar párrafos tal cual |
| Fuentes | Enlaces inline en el cuerpo del texto |
| Titulares | Estilo ANXiNA: gancho natural, personal, sin clickbait vacío |
| Cifras | Lista, caja destacada o tabla según lo que lea mejor |
| Emojis | **Nunca** en el cuerpo del post (delatan texto generado por IA). Cajas, títulos y listas van sin emoji |
| Monedas | No convertir a dólares por defecto. Solo hacerlo cuando el dato lo pida; en ese caso, buscar el precio actualizado en internet |
| Terminología | Nunca "reseñador"; usar "analista" o "crítico" según el más viable |

### Categorías habituales

Dispositivos · Videojuegos · IA · Reseñas · Vehículos · Nota

Voz de referencia (cómo se le habla al lector): `valve-steam-frame-videos-filtrados/valve-steam-frame-videos-filtrados-anxina.html`. El del PS6 sirve de ritmo; este es el tono.

---

## Voz: que no suene a IA

El lector tiene que sentir que le estás contando la nota, no que leíste un briefing y lo recitaste. El problema casi nunca es una palabra suelta. Es el ritmo, las construcciones y la falta de alguien detrás del texto.

La lista de Wikipedia ([Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing)) y las guías de 2025–2026 coinciden: el detector más fiable es estructural. Una palabra “prohibida” no condena. Un patrón repetido sí.

### Lo que delata (en orden de daño)

1. **Nadie te está hablando.** El post describe el tema en tercera persona, equilibrado, sin “tú” ni “nosotros” ni un juicio. Suena a ficha. El lead tiene que meter al lector en la escena (“Si esperabas…”, “mejor ve abriendo otra cuenta”).
2. **Ritmo de metrónomo.** Párrafos de dos o tres oraciones medianas, todas del mismo largo. La prosa humana es desigual: una de cuatro palabras, luego una larga, luego un corte. Exige varias oraciones de menos de cinco palabras y al menos un par de más de treinta.
3. **“No es X, es Y.”** El giro de contraste que finge profundidad: “No es un render. Es Valve explicando…”. “La promesa no es ser otro Quest. Es ser SteamOS…”. Una vez, si se gana el chiste, pasa. Tres o cuatro en el mismo post es huella. Igual: “no solo X, sino también Y”, “no se trata de X, sino de Y”.
4. **Regla de tres.** Adjetivos, beneficios o cláusulas de a tres (“claro, conciso y convincente”; “unboxing, primer encendido y dongle” usado como cadencia, no como lista real). Una tríada está bien. Cada párrafo con exactamente tres cosas es máquina. Las fichas de specs en caja sí pueden ser listas: eso es dato, no prosa.
5. **Raya em (—) de muleta.** Un paréntesis, una coma o un punto suelen leer mejor. La raya no está prohibida; está prohibido usarla en cada párrafo para respirar.
6. **Aclarar la garganta.** Primera oración del párrafo que no dice nada: “Cuando se trata de X…”, “Hay varios factores a considerar…”, “Y aquí viene lo interesante”. Casi siempre el dato está en la segunda oración. Bórrala.
7. **Hedging de brochure.** “Es importante mencionar”, “cabe destacar”, “vale la pena señalar”, “sin embargo” / “además” / “dicho esto” arrancando párrafo. En inglés: *delve, tapestry, landscape, realm, testament, pivotal, underscore, robust, moreover, furthermore*. En español: *en este sentido, en el panorama actual, se trata de, una auténtica revolución, sin duda, en definitiva, en resumen, a lo largo y ancho*.
8. **Inflar significado.** Cada hecho “marca un hito”, “subraya la importancia”, “refleja un cambio más amplio”. Si el dato no es histórico, no lo trates como si lo fuera.
9. **Expertos fantasmas.** “Los analistas coinciden”, “observadores señalan”, “varios medios”. Nombra a la persona o al medio, o cállate la atribución.
10. **Cierre que recita el lead.** El último párrafo no es un resumen de lo que ya leíste. Es un juicio: ¿compras, esperas, lo dejas pasar? Luego la firma.

### Español latinoamericano neutro

Conversacional, no formal. Neutro, no “sin acento”: se entiende en México, Colombia, Chile, Argentina o Perú sin que el lector sienta que le escribieron en otro país.

**Usar (LatAm compartido):** `tú` (nunca *vos* ni *vosotros*), celular, computadora, lentes, tienda, pantalla, control, visor.

**No usar:**
- Mexicanismos: *neta, chido, órale, andabas, le entras, te tocó, anaquel, lentes de ver, platicar* como marca de tono, *paso* como “no compro”.
- Español de España: *móvil, ordenador, gafas* por defecto, *vosotros, mola, tío*.
- Rioplatense: *vos, che, laburo, pibe*.
- Calcos: *in the wild* → no *en la calle*. Según el caso: *ya salió, ya está público, ya circula, ya se filtró*.

Una muletilla local de vez en cuando no salva el tono; cinco en 800 palabras se leen a disfraz. Habla. Corta. Opina. No imites a un influencer de ningún país.

El post del Steam Frame (`valve-steam-frame-videos-filtrados/`) es la **muestra de voz**. Antes de redactar, pégalo y copia ese trato, no el tema. El del PS6 sirve si hace falta más ritmo de “cuenta de ahorro”, no de dialecto.

### Cómo suena ANXiNA (lo que se aprendió de un rewrite humano)

Esto no es un disfraz de coloquial. Es cómo cuenta la nota alguien que ya se la leyó:

- **Marcadores hablados, no de brochure.** *Pues…*, *resulta que*, *o sea*, *y ojo*, *la verdad*. Van donde iría una pausa al contarlo. No los apiles; uno o dos por sección alcanzan. *La verdad* sí; *la neta* no.
- **Punto suspensivo de habla.** “pues… ya lo hicieron” / “el visor… ni señas”. Es una pausa, no un adorno. Tres puntos, no raya em.
- **Un punchline que recorta.** “todo lo que necesitas saber, menos el precio.” El dato está; el chiste es lo que falta. A veces cierra el párrafo con dos palabras dichas: “Así nomás.”
- **Juicio a mitad del post, no solo al cierre.** “Se nota que le pusieron cariño al producto, aunque todavía no se pueda comprar.” El humano opina mientras enseña la caja. La máquina espera al último párrafo. Si el juicio pide eco, una pregunta corta al lector: “Medio contradictorio, ¿no?”
- **Cierre blando.** “el calendario de Valve es otro tema” / “prefiero ver el juego como se supone que debe verse. Pero bueno, el secreto de Rockstar ya es otro tema.” Gana a un corte que quiere sonar ingenioso.
- **H2 cortos.** “El dongle es la clave”, “¿Qué trae la caja?”. No “El dongle, que es lo que de verdad importa”.
- **Frases que viajan.** *ni señas*, *por las nubes*, *te dejamos acá*, *sin querer*. No son slang de un país; se entienden en LatAm.
- **Oraciones que corren.** “el manual, el unboxing y hasta cómo se prende” en una sola línea. No fingas burstiness con tres fragmentos seguidos (“Unboxing. Primer encendido. El dongle.”).
- **Transmitir, no streamear**, si la frase se entiende igual. El anglicismo queda para nombres (Steam) y el sondeo, no para explicar el dongle.

Antes de redactar, pega 150–300 palabras de ese post y copia **ritmo y trato al lector**, no el tema.

Después del primer borrador, pasa esto:

- Léelo en voz alta. Donde suene a comunicado, reescribe.
- Busca `no es`, `no solo`, `sino`, `además`, `cabe`, `importante`, `en este sentido`, `en definitiva` y las rayas `—`. Recorta.
- Revisa que haya alguien en el texto: tú, nosotros, un “si ya tienes X…”.
- Tira la primera oración de cualquier párrafo que solo anuncie la que sigue.
- El cierre no puede parafrasear el título.
- Si pasas de 600 palabras de prosa, corta una sección. El sondeo no cuenta.

---

## Formato de entrega

Cada post debe incluir esto **antes** del HTML (como comentario HTML al inicio del archivo o en el chat):

```
TÍTULO: ...
META DESCRIPCIÓN: ... (150–160 caracteres)
PERMALINK: ... (palabras clave separadas por guiones, sin espacios ni acentos)
CATEGORÍA: ...
ETIQUETAS: ...
IMAGEN SUGERIDA: ... (descripción para buscar o generar; no el archivo)
REDES SOCIALES: ... (texto corto para compartir; termina con el cierre fijo)
```

### Redes sociales (texto para compartir)

Versión corta y con gancho del post, para Facebook / X / Instagram. Va **dentro del comentario de metadatos**, no en el HTML que se pega en Blogger.

- 2–4 líneas, tono conversacional, que dé curiosidad
- Incluir 2–4 hashtags relevantes
- **Terminar siempre** con esta línea exacta:

```
👉 Lee el post completo visita ANXiNA.xyz
```

**Ejemplo:**

```
Brasil ya vende el DOBLE de autos eléctricos que México… y la brecha crece.
¿Puede Olinia, el eléctrico hecho en México, cambiar el juego?
#Electromovilidad #Olinia #AutosElectricos #Mexico
👉 Lee el post completo visita ANXiNA.xyz
```

> Nota: los emojis están prohibidos en el **cuerpo del post**. La línea de cierre de **redes sociales** conserva el `👉` porque es una convención fija de marca y va en el comentario de metadatos, no en el HTML que se publica.

### Permalink (URL personalizada en Blogger)

Formato como las URLs de anxina.xyz: palabras clave unidas con guiones, sin espacios, sin acentos ni caracteres especiales.

**Ejemplos:**
- `Valve-Steam-Machine-Videojuegos-PC-Gaming-PlayStation-SteamOS-Controller`
- `Brasil-Mexico-Electromovilidad-Olinia-Autos-Electricos-Vehiculos-BYD`
- `GTA-VI-Videojuegos-Rockstar-Take-Two-Sony-Xbox`

Incluir: tema principal, marcas/productos relevantes, categoría o tipo de nota. Pegar en Blogger → opciones del post → **Enlace permanente** → **URL personalizada**.

Luego el bloque:

```
--- HTML PARA BLOGGER ---
```

El HTML se guarda **dentro de la carpeta del post**, junto al archivo de información, con nombre descriptivo. Ejemplo: `brasil-electromovilidad-olinia/brasil-electromovilidad-olinia-anxina.html`.

Para un post nuevo: crear la carpeta (mismo slug que el HTML, sin `-anxina.html`), poner ahí la info y el HTML.

---

## Cierre obligatorio (firma)

La firma es **siempre el último párrafo del post** y va **pegada al párrafo de conclusión**, sin que el poll ni las fuentes queden en medio (si no, la firma se lee fuera de lugar). Orden correcto al final del post:

```
… contenido → poll (si aplica) → fuentes / nota final → párrafo de conclusión → firma
```

Firma exacta:

```html
<p>Las cosas como son. Y en cultura digital: Anxina.</p>
```

---

## HTML compatible con Blogger y tema oscuro

ANXiNA usa tema claro/oscuro. Los posts deben verse bien en **ambos**, pero el tema oscuro es el que más problemas da si se usan fondos claros.

### Etiquetas permitidas

`<p>` · `<h2>` · `<h3>` · `<strong>` · `<em>` · `<ul>` · `<li>` · `<blockquote>` · `<hr>` · `<a>`

Evitar `<div>` con clases personalizadas (Blogger puede ignorarlas). Los estilos van **inline** en los cuadros destacados.

### ❌ No usar

```html
<!-- Fondo claro: texto claro del tema oscuro queda ilegible -->
<div style="background-color:#f4f4f4; border-left:4px solid #333;">
```

### ✅ Caja destacada (datos, “El dato”)

```html
<div style="border-left:4px solid #6eb5ff;background:rgba(255,255,255,0.08);padding:16px 20px;margin:24px 0;border-radius:0 6px 6px 0;color:inherit;">
<p style="margin:0;color:inherit;"><strong>El dato:</strong> Texto aquí.</p>
</div>
```

### ✅ Caja con lista

```html
<div style="border-left:4px solid #6eb5ff;background:rgba(255,255,255,0.08);padding:16px 20px;margin:24px 0;border-radius:0 6px 6px 0;color:inherit;">
<p style="margin:0 0 8px 0;color:inherit;"><strong>Título del bloque</strong></p>
<ul style="margin:0;padding-left:20px;color:inherit;">
<li style="color:inherit;"><strong>Item:</strong> valor</li>
</ul>
</div>
```

### Citas

```html
<blockquote>
<p>“Cita textual breve.”</p>
<p style="margin-bottom:0;"><em>— Nombre, cargo</em></p>
</blockquote>
```

### Enlaces

```html
<a href="https://..." rel="noopener" target="_blank">Texto del enlace</a>
```

### Separadores entre secciones

```html
<hr />
```

---

## Ejemplo de estructura

```html
<!--
TÍTULO: ...
META DESCRIPCIÓN: ...
PERMALINK: Palabra-Clave-Tema-Categoria-Marcas
CATEGORÍA: ...
ETIQUETAS: ...
IMAGEN SUGERIDA: ...
-->

<p>Lead — lo más importante en el primer párrafo.</p>
<p>Segundo párrafo que engancha o contextualiza.</p>

<hr />

<h2>Subtítulo de sección</h2>
<p>Cuerpo reescrito con enlaces inline a fuentes.</p>

<!-- caja de datos si aplica -->

<hr />

<h2>Otra sección</h2>
<p>...</p>

<p><em>Información adicional en <a href="..." rel="noopener" target="_blank">Fuente</a>.</em></p>

<p>Párrafo de conclusión que cierra el tema.</p>

<p>Las cosas como son. Y en cultura digital: Anxina.</p>
```

---

## Sondeo / encuesta (interacción) — caso especial

Para subir la interacción, los posts que lo ameriten pueden incluir **un sondeo** al final (antes de fuentes/cierre). Es la **única excepción** a las reglas de “solo etiquetas permitidas / sin `<div>` / sin JS”: el sondeo sí usa `<div>`, estilos inline y un `<script>`.

- **Bloque reutilizable:** `poll-snippet.html` (copiar/pegar y editar).
- **Conteo:** [Abacus](https://jasoncameron.dev/abacus/) — gratis, sin registro, con CORS. Los totales son **globales**; cada lector vota una vez por dispositivo (se guarda en `localStorage`).
- **Tema oscuro:** ya viene con la caja `#6eb5ff` y fondo translúcido de ANXiNA.

### Reglas al insertarlo

1. `data-anxina-poll="..."` debe ser **único por post** (ej. `gta6-fecha-2026`). Si se repite, los posts comparten votos.
2. No cambiar `data-ns="anxina.xyz"` (namespace del contador).
3. Cada `<button>` lleva un `data-key` corto, **sin acentos ni espacios** y único dentro del sondeo.
4. Mínimo 2 opciones. Al último botón déjale `margin:0`.
5. El `<script>` va **minificado en una sola línea** a propósito (sobrevive a la opción “Convertir saltos de línea” de Blogger). No desformatear.

### Blogger

- Pegar en la vista **HTML** y **no** volver a “Redacción/Compose” (Blogger reescribe el HTML y puede romper el `<script>`).
- Probar el voto una vez publicado: al votar deben aparecer barras con porcentajes y el total.

---

## Archivos de referencia

- Post de ejemplo: `brasil-electromovilidad-olinia/brasil-electromovilidad-olinia-anxina.html`
- Post con sondeo integrado: `ps6-precio-rampocalipsis-sony/ps6-precio-rampocalipsis-sony-anxina.html`
- Plantilla de sondeo: `poll-snippet.html` (sigue en la raíz)
