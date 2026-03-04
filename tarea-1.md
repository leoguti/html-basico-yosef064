# Tarea 1 - Tu primera página HTML

## ¿Qué vas a hacer?

Vas a crear un archivo llamado `mi-pagina.html` que se abre en el navegador como una página web real.

## Paso 1: Crear el archivo

1. En este repositorio, haz clic en **"Add file"** → **"Create new file"**
2. En el nombre del archivo escribe: `mi-pagina.html`
3. Copia y pega este código **exactamente como está**:

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Mi Primera Página</title>
</head>
<body>
    <h1>Hola, soy [TU NOMBRE]</h1>
    <p>Esta es mi primera página web. La hice yo desde cero.</p>
    <p>Estudio en el Colegio Salesiano de Duitama.</p>
</body>
</html>
```

4. **Cambia `[TU NOMBRE]` por tu nombre real**
5. En el mensaje del commit escribe: `Crear mi primera página HTML`
6. Selecciona **"Commit directly to the main branch"**
7. Clic en **"Commit changes"**

## Paso 2: Ver tu página

1. Haz clic en el archivo `mi-pagina.html` que acabas de crear
2. Arriba a la derecha del código, haz clic en **"Raw"**
3. Verás el código en texto plano. Copia la URL del navegador
4. Entra a https://htmlpreview.github.io/ y pega la URL
5. ¡Deberías ver tu página web!

(En la Tarea 3 vamos a publicarla de verdad en internet con GitHub Pages)

## ¿Qué significa cada línea?

```
<!DOCTYPE html>          ← Le dice al navegador: "esto es HTML"
<html lang="es">         ← Empieza el documento. lang="es" = español
<head>                   ← Información SOBRE la página (no se ve)
    <meta charset="UTF-8">  ← Permite usar ñ, tildes, emojis
    <title>Mi Primera Página</title>  ← Lo que aparece en la pestaña
</head>                  ← Fin de la información
<body>                   ← Empieza lo que SÍ SE VE en la página
    <h1>...</h1>         ← Título grande (h1 = heading 1)
    <p>...</p>           ← Párrafo de texto (p = paragraph)
</body>                  ← Fin de lo visible
</html>                  ← Fin del documento
```

## Conceptos clave

- **Etiqueta (tag):** Las cosas entre `< >`. Ejemplo: `<h1>`, `<p>`, `<body>`
- **Etiqueta de apertura y cierre:** `<h1>` abre, `</h1>` cierra. Todo lo de adentro es el contenido
- **Anidamiento:** Las etiquetas van unas dentro de otras, como cajas dentro de cajas:
  ```
  <html>
      <body>
          <h1>Texto</h1>
      </body>
  </html>
  ```

## ¿Listo?

Cuando termines, pasa a la [Tarea 2](tarea-2.md).
