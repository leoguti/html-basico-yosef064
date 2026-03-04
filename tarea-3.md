# Tarea 3 - Publicar tu página en internet

## ¿Qué vas a hacer?

Vas a activar **GitHub Pages** en tu repositorio para que tu página `mi-pagina.html` sea visible para cualquier persona en el mundo.

## Paso 1: Activar GitHub Pages

1. Ve a la pestaña **Settings** (⚙️) de este repositorio
2. En el menú de la izquierda, busca **Pages**
3. En **"Source"**, selecciona **"Deploy from a branch"**
4. En **"Branch"**, selecciona **"main"** y deja **"/ (root)"**
5. Clic en **Save**
6. Espera 1-2 minutos

## Paso 2: Ver tu página en vivo

Tu página estará en:

```
https://[TU-USUARIO].github.io/html-basico/mi-pagina.html
```

Cambia `[TU-USUARIO]` por tu nombre de usuario de GitHub.

Por ejemplo, si tu usuario es `NadiaM3100`, tu página estará en:
```
https://NadiaM3100.github.io/html-basico/mi-pagina.html
```

## Paso 3: Crear una página de inicio

Crea un archivo llamado `index.html` con este contenido:

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Mi Sitio Web</title>
</head>
<body>
    <h1>Bienvenido a mi sitio web</h1>
    <p>Soy [TU NOMBRE] del Colegio Salesiano de Duitama.</p>

    <h2>Mis páginas</h2>
    <ul>
        <li><a href="mi-pagina.html">Mi primera página</a></li>
    </ul>

    <p><em>Hecho con HTML puro - Escuela OSM + Vibe Coding 2026</em></p>
</body>
</html>
```

Commit con mensaje: `Crear página de inicio index.html`

Ahora tu sitio web tiene una portada en:
```
https://[TU-USUARIO].github.io/html-basico/
```

## ¿Por qué se llama index.html?

`index.html` es el archivo que el navegador busca **automáticamente** cuando visitas una carpeta web. Es como la puerta de entrada de tu sitio.

## ¿Listo?

Tu página está en internet. Compártele el enlace a alguien. Pasa a la [Tarea 4](tarea-4.md).
