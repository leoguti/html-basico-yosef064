# Guía de la Charla - HTML Básico (para el profesor)

**Duración estimada de la charla:** 20-25 minutos
**Después:** los estudiantes trabajan en sus repos con las tareas 1-5

---

## Antes de empezar

- Tener abierto el mapa del Salesiano: https://leoguti.github.io/mapa-salesiano/
- Tener abierto el código fuente: https://github.com/leoguti/mapa-salesiano/blob/main/index.html
- Compartir pantalla por Meet o proyector

---

## PARTE 1: Conectar con lo que ya saben (5 min)

### Abrir el mapa del Salesiano

> "¿Se acuerdan de esto? El mapa que hicimos juntos. Cada uno de ustedes puso un marcador aquí. Esto está en internet, cualquier persona del mundo puede verlo."

**Hacer clic en un marcador para que se vea el popup.**

> "Esto es una PÁGINA WEB. Pero ¿de qué está hecha? ¿Cómo sabe el navegador qué mostrar?"

### Mostrar el código fuente

**Abrir el `index.html` en GitHub (la vista de código, no la página).**

> "Esto es lo que hay detrás. Este archivo de texto es lo que el navegador lee para dibujar la página. Se llama HTML."

> "Ustedes ya editaron este archivo cuando pusieron su marcador. Ya tocaron HTML sin saberlo."

**Señalar las líneas que ellos editaron (los bloques de `L.marker`).**

---

## PARTE 2: ¿Qué es HTML? (5 min)

> "HTML significa HyperText Markup Language. Lenguaje de Marcado. ¿Qué quiere decir 'marcado'?"

**Analogía: Imaginen un documento de Word.**
> "En Word ustedes pueden poner un título grande, un párrafo, una lista con puntos, una imagen. Word lo hace con botones. HTML hace lo mismo pero con TEXTO. En vez de botones, usas etiquetas."

### Mostrar la estructura básica

**Escribir en el pad compartido o en el proyector:**

```
<h1>Esto es un título</h1>
<p>Esto es un párrafo</p>
```

> "Las cosas entre < > se llaman ETIQUETAS o TAGS. Siempre van en pares: una abre y otra cierra."

> "`<h1>` le dice al navegador: 'lo que viene es un título grande'. `</h1>` le dice: 'aquí termina el título'."

> "`<p>` es párrafo. P de 'paragraph' en inglés."

### Demostración en vivo (1 minuto)

**Abrir un archivo HTML nuevo en el navegador para mostrar el resultado.**

Opción rápida: Abrir https://htmlpreview.github.io/ o usar las DevTools del navegador:
1. Click derecho → Inspeccionar → Console
2. Escribir: `document.body.innerHTML = '<h1>Hola Salesiano</h1><p>Esto es HTML</p>'`
3. Se actualiza la página en vivo

> "Miren: yo escribí texto con etiquetas y el navegador lo convirtió en una página. Eso es HTML."

---

## PARTE 3: La estructura de una página (5 min)

**Mostrar esto en el proyector:**

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Mi Página</title>
    </head>
    <body>
        <h1>Hola</h1>
        <p>Contenido aquí</p>
    </body>
</html>
```

> "Toda página HTML tiene esta estructura. Piensen en una carta:"

```
Sobre de la carta     →  <html>
  Datos del remitente →  <head> (información, no se ve)
  La carta misma      →  <body> (lo que se ve en la página)
```

> "El `<head>` tiene información SOBRE la página: el título que aparece en la pestaña del navegador, el idioma, etc. Pero no se ve."

> "El `<body>` es todo lo que SÍ se ve: textos, imágenes, listas, enlaces."

### Las etiquetas más comunes

**Mostrar esta lista:**

| Etiqueta | Qué hace | Ejemplo |
|---|---|---|
| `<h1>` a `<h6>` | Títulos (del más grande al más pequeño) | `<h1>Título</h1>` |
| `<p>` | Párrafo | `<p>Un texto cualquiera</p>` |
| `<strong>` | Negrita | `<strong>importante</strong>` |
| `<a href="URL">` | Enlace (link) | `<a href="https://google.com">Ir a Google</a>` |
| `<img src="URL">` | Imagen | `<img src="foto.jpg">` |
| `<ul>` + `<li>` | Lista con puntos | `<ul><li>uno</li><li>dos</li></ul>` |

> "No se preocupen por memorizarlas. Las van a aprender usándolas. Y cuando no se acuerden, le preguntan a la IA."

---

## PARTE 4: Conectar con el mapa (3 min)

**Volver al código del index.html del mapa.**

> "Miren el mapa del Salesiano otra vez. Línea 1:"

```html
<!DOCTYPE html>
```

> "¿Lo reconocen? Es lo mismo que les acabo de enseñar."

**Señalar las etiquetas que ya conocen:**
- `<html>`, `<head>`, `<body>` → la estructura
- `<title>` → el título en la pestaña
- `<h1>` → "Mapa del Salesiano - Nuestros Lugares Favoritos"
- `<p>` → "Escuela OSM + Vibe Coding..."
- `<div>` → un contenedor (como una caja invisible)
- `<style>` → los colores y tamaños (eso es CSS, lo vemos después)
- `<script>` → la lógica del mapa (eso es JavaScript, lo vemos después)

> "El mapa tiene 3 lenguajes mezclados: HTML para la estructura, CSS para los colores, y JavaScript para la interacción. Hoy vamos a dominar el primero: HTML."

---

## PARTE 5: Ahora les toca a ustedes (2 min)

> "Cada uno tiene su propio repositorio con instrucciones paso a paso. Van a crear su primera página HTML desde cero, publicarla en internet, y al final van a probar cómo la IA les puede ayudar a escribir código."

> "Pero la regla es esta: NO acepten código de la IA que no entiendan. Por eso primero aprendemos las bases."

**Dar los enlaces de los repos a cada estudiante.**

> "Abran su repo, lean el README, y empiecen con la Tarea 1."

---

## Mientras trabajan

- Circular por el salón
- Asegurarse de que cada uno pudo crear `mi-pagina.html`
- Los que van adelantados pueden avanzar a Tarea 2 y 3
- La Tarea 4 (romper y arreglar) es la más divertida, motivarlos a llegar ahí
- La Tarea 5 (IA) es el premio al final

**Errores comunes:**
- Olvidar cerrar una etiqueta: `<h1>texto` sin `</h1>`
- Poner el contenido fuera del `<body>`
- Escribir el nombre del archivo sin `.html`
- No seleccionar "Commit directly to main branch"
- GitHub Pages tarda 1-2 min en actualizar

---

## Para monitorear progreso

Revisar en cada repo de estudiante:
1. ¿Existe `mi-pagina.html`? → Completó Tarea 1
2. ¿Tiene `<ul>`, `<a>`, `<img>`? → Completó Tarea 2
3. ¿GitHub Pages activado? → Completó Tarea 3
4. ¿Tiene commits de "Experimento"? → Hizo Tarea 4
5. ¿Tiene `<table>`? → Llegó a Tarea 5

Puedo revisar todo esto automáticamente cuando me lo pidas.
