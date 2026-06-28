# Guía de posts — ANXiNA

Referencia persistente para redactar posts de [ANXiNA](https://www.anxina.xyz/) a partir de archivos `.txt` y publicarlos en Blogger.

---

## Flujo de trabajo

1. El usuario coloca un `.txt` con información cruda en esta carpeta.
2. Se redacta el post en español mexicano y se genera un `.html`.
3. El usuario pega el HTML en Blogger → editor → vista **HTML**.
4. Se configuran título, etiquetas e imagen destacada con los metadatos entregados.

---

## Perfil editorial

| Aspecto | Criterio |
|--------|----------|
| Tono | Cercano y conversacional, sin perder credibilidad |
| Extensión | 700–1,000 palabras |
| Estructura | Lead fuerte + subtítulos (H2/H3) + bloque de datos al final de sección si aplica |
| Español | Mexicano |
| Uso del .txt | Reescritura completa; no copiar párrafos tal cual |
| Fuentes | Enlaces inline en el cuerpo del texto |
| Titulares | Estilo ANXiNA: gancho natural, personal, sin clickbait vacío |
| Cifras | Lista, caja destacada o tabla según lo que lea mejor |

### Categorías habituales

Dispositivos · Videojuegos · IA · Reseñas · Vehículos · Nota

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
👉 Si quieres ver el post completo visita ANXiNA.xyz
```

**Ejemplo:**

```
🔋 Brasil ya vende el DOBLE de autos eléctricos que México… y la brecha crece.
¿Puede Olinia, el eléctrico hecho en México, cambiar el juego?
#Electromovilidad #Olinia #AutosElectricos #Mexico
👉 Si quieres ver el post completo visita ANXiNA.xyz
```

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

El archivo se guarda en esta carpeta con nombre descriptivo, por ejemplo: `brasil-electromovilidad-olinia-anxina.html`.

---

## Cierre obligatorio

**Siempre** como último párrafo del cuerpo del post (después de fuentes o nota final):

```html
<p>Las cosas como son. Y en cultura digital… son Anxina.</p>
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
<p style="margin:0;color:inherit;"><strong>⚡ El dato:</strong> Texto aquí.</p>
</div>
```

### ✅ Caja con lista

```html
<div style="border-left:4px solid #6eb5ff;background:rgba(255,255,255,0.08);padding:16px 20px;margin:24px 0;border-radius:0 6px 6px 0;color:inherit;">
<p style="margin:0 0 8px 0;color:inherit;"><strong>📊 Título del bloque</strong></p>
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

<p>Las cosas como son. Y en cultura digital… son Anxina.</p>
```

---

## Archivo de referencia

Post de ejemplo en este repositorio: `brasil-electromovilidad-olinia-anxina.html`
