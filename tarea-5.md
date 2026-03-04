# Tarea 5 - Tu primer contacto con IA y código

## ¿Por qué primero aprendimos HTML?

Porque cuando le pidas a una IA que escriba código, necesitas **entender lo que te da**. Si no sabes qué es un `<h1>` o un `<p>`, no puedes verificar si la IA hizo bien su trabajo.

Ahora que sabes HTML básico, puedes usar IA con criterio.

## Paso 1: Abrir GitHub Copilot

1. Abre este repositorio en tu navegador
2. Presiona la tecla **`.`** (punto) en tu teclado
3. Se abre **github.dev** - un editor de código en el navegador
4. A la izquierda, abre el archivo `mi-pagina.html`

## Paso 2: Pedir algo a Copilot

1. En github.dev, abre el **chat de Copilot** (ícono de Copilot en el panel izquierdo o `Ctrl+Shift+I`)
2. Escríbele algo como:

```
Agrega una sección "Mi horario de clases" con una tabla HTML
que tenga las columnas: Día, Materia, Hora.
Agrega 3 filas de ejemplo.
```

3. Copilot va a generar código HTML
4. **ANTES de aceptar**, revisa el código:
   - ¿Ves etiquetas que conoces? (`<h2>`, `<p>`, etc.)
   - ¿Hay etiquetas nuevas? (probablemente `<table>`, `<tr>`, `<td>`, `<th>`)
   - ¿El contenido tiene sentido?

5. Si te parece bien, acepta el código

## Paso 3: Entender lo que la IA generó

Seguramente Copilot generó algo como esto:

```html
<h2>Mi horario de clases</h2>
<table>
    <tr>
        <th>Día</th>
        <th>Materia</th>
        <th>Hora</th>
    </tr>
    <tr>
        <td>Lunes</td>
        <td>Matemáticas</td>
        <td>7:00 AM</td>
    </tr>
</table>
```

Nuevas etiquetas:
| Etiqueta | Significado |
|---|---|
| `<table>` | Define una tabla |
| `<tr>` | Table Row = una fila |
| `<th>` | Table Header = encabezado (negrita) |
| `<td>` | Table Data = celda normal |

## Paso 4: Modificar lo que la IA hizo

1. Cambia los datos de ejemplo por tu horario real
2. Agrega o quita filas
3. Haz commit con mensaje: `Agregar tabla de horario con ayuda de Copilot`

## La regla de oro del Vibe Coding

```
La IA escribe código → Tú lo revisas → Tú lo entiendes → Tú lo aceptas o corriges
```

Nunca aceptes código que no entiendas. Siempre pregunta: "¿qué hace esta línea?"

## Paso 5 (Bonus): Pide algo más

Prueba pedirle a Copilot:
- "Agrega un pie de página con la fecha de hoy"
- "Cambia el color del título a azul"
- "Agrega un enlace a mi perfil de GitHub"

Cada vez que genere código, **revísalo antes de aceptar**.

---

**¡Felicidades!** Ya sabes crear HTML desde cero, publicarlo en internet, y usar IA para ayudarte. Estás listo para proyectos más grandes.
