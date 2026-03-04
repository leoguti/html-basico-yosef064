# Tarea 2 - Agregar más contenido a tu página

## ¿Qué vas a hacer?

Vas a editar `mi-pagina.html` para agregarle más elementos HTML: títulos, listas, enlaces e imágenes.

## Paso 1: Agregar una lista y un enlace

1. Abre `mi-pagina.html` en este repositorio
2. Haz clic en el **lápiz** para editar
3. Reemplaza TODO el contenido del `<body>` con esto:

```html
<body>
    <h1>Hola, soy [TU NOMBRE]</h1>
    <p>Esta es mi primera página web. La hice yo desde cero.</p>

    <h2>Sobre mí</h2>
    <p>Estudio en el <strong>Colegio Salesiano</strong> de Duitama, Boyacá.</p>

    <h2>Mis cosas favoritas</h2>
    <ul>
        <li>Mi comida favorita: [ESCRIBE AQUÍ]</li>
        <li>Mi materia favorita: [ESCRIBE AQUÍ]</li>
        <li>Mi lugar favorito de Duitama: [ESCRIBE AQUÍ]</li>
    </ul>

    <h2>Enlaces</h2>
    <p>Mira el mapa que hicimos juntos:</p>
    <a href="https://leoguti.github.io/mapa-salesiano/">Mapa del Salesiano</a>

    <h2>Mi lugar favorito</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/80/Duitama_Boyac%C3%A1.jpg/640px-Duitama_Boyac%C3%A1.jpg" alt="Duitama" width="400">
    <p>Duitama, mi ciudad.</p>
</body>
```

4. **Cambia los `[ESCRIBE AQUÍ]` y `[TU NOMBRE]` por tus datos**
5. Commit con mensaje: `Agregar lista, enlace e imagen a mi página`

## Nuevas etiquetas que aprendiste

| Etiqueta | Qué hace | Ejemplo |
|---|---|---|
| `<h2>` | Título mediano (subtítulo) | `<h2>Sobre mí</h2>` |
| `<strong>` | Texto en **negrita** | `<strong>importante</strong>` |
| `<ul>` | Lista con puntos | Envuelve los `<li>` |
| `<li>` | Cada punto de la lista | `<li>Pizza</li>` |
| `<a href="URL">` | Enlace (link) que puedes clic | `<a href="https://...">Texto</a>` |
| `<img src="URL">` | Muestra una imagen | `<img src="https://..." alt="descripción">` |

## Paso 2: Personaliza más (opcional, si te queda tiempo)

Prueba agregar más cosas. Aquí tienes ideas:

```html
<!-- Título más pequeño -->
<h3>Un título más pequeño</h3>

<!-- Texto en cursiva -->
<em>Este texto sale en cursiva</em>

<!-- Una línea horizontal -->
<hr>

<!-- Otra imagen (busca una URL de imagen en internet) -->
<img src="URL_DE_LA_IMAGEN" alt="descripción" width="300">
```

**Nota:** Las líneas que empiezan con `<!--` y terminan con `-->` son **comentarios**. No se ven en la página, son notas para el programador. ¡Ya las conoces del mapa del Salesiano!

## ¿Listo?

Cuando termines, pasa a la [Tarea 3](tarea-3.md).
