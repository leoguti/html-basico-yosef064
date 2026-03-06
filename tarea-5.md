# Tarea 5 - Tu primer contacto con IA y código

## ¿Por qué primero aprendimos HTML?

Porque cuando le pidas a una IA que escriba código, necesitas **entender lo que te da**. Si no sabes qué es un `<h1>` o un `<p>`, no puedes verificar si la IA hizo bien su trabajo.

Ahora que sabes HTML básico, puedes usar IA con criterio.

## Paso 0: Activar Copilot en tu cuenta (solo la primera vez)

**IMPORTANTE:** Antes de empezar, necesitas activar Copilot Free en tu cuenta de GitHub. Solo se hace una vez.

1. Ve a **github.com** e inicia sesión
2. Haz clic en tu **foto de perfil** (arriba a la derecha)
3. Haz clic en **"Copilot settings"**
   - O ve directo a: https://github.com/settings/copilot
4. Haz clic en **"Start using Copilot Free"**
5. Acepta los términos si te lo pide

¡Listo! Ya tienes Copilot activado. Esto incluye 50 chats gratis al mes.

## Paso 1: Abrir el editor en el navegador

1. Abre tu repositorio en el navegador (la página principal donde ves tus archivos)
2. Presiona la tecla **`.`** (punto) en tu teclado
3. Se abre **github.dev** - un editor de código en el navegador (se ve como VS Code)
4. Espera unos segundos a que cargue completamente

## Paso 2: Abrir el chat de Copilot

Hay **3 formas** de abrir Copilot. Prueba en este orden:

### Opción A: Atajo de teclado
- Presiona **`Ctrl + Shift + I`** (las 3 teclas al mismo tiempo)
- Se abre un panel de chat a la derecha

### Opción B: Ícono en la barra lateral
- Mira la barra de íconos de la **izquierda**
- Busca el ícono de **Copilot** (parece un dibujo de un copiloto/robot con dos círculos, está abajo de todo)
- Haz clic en ese ícono
- Se abre el panel de chat

### Opción C: Desde el menú
- Haz clic en el menú **☰** (tres líneas horizontales) arriba a la izquierda
- Ve a **View** (Ver)
- Busca **Chat** o **Copilot Chat**
- Haz clic

**Si ninguna opción funciona:** Asegúrate de haber iniciado sesión en GitHub. Copilot gratuito viene incluido con tu cuenta.

## Paso 3: Pedir algo a Copilot

1. En el chat que se abrió, escribe esto:

```
Agrega una sección "Mi horario de clases" con una tabla HTML
que tenga las columnas: Día, Materia, Hora.
Agrega 3 filas de ejemplo.
```

2. Presiona **Enter** para enviar
3. Copilot va a generar código HTML
4. **ANTES de aceptar**, revisa el código:
   - ¿Ves etiquetas que conoces? (`<h2>`, `<p>`, etc.)
   - ¿Hay etiquetas nuevas? (probablemente `<table>`, `<tr>`, `<td>`, `<th>`)
   - ¿El contenido tiene sentido?

5. Si te parece bien, haz clic en **"Apply"** o **"Insert at Cursor"** para ponerlo en tu archivo

## Paso 4: Entender lo que la IA generó

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

## Paso 5: Guardar los cambios

En github.dev los cambios NO se guardan automáticamente. Debes hacer commit:

1. Haz clic en el ícono de **Source Control** en la barra izquierda (parece una ramificación, el tercer ícono)
2. Verás los archivos que cambiaste
3. Escribe un mensaje: `Agregar tabla de horario con ayuda de Copilot`
4. Haz clic en **"Commit & Push"** (✓)

## Paso 6: Modificar lo que la IA hizo

1. Cambia los datos de ejemplo por tu horario real
2. Agrega o quita filas
3. Haz otro commit

## La regla de oro del Vibe Coding

```
La IA escribe código → Tú lo revisas → Tú lo entiendes → Tú lo aceptas o corriges
```

Nunca aceptes código que no entiendas. Siempre pregunta: "¿qué hace esta línea?"

## Paso 7 (Bonus): Pide algo más

Prueba pedirle a Copilot:
- "Agrega un pie de página con la fecha de hoy"
- "Cambia el color del título a azul"
- "Agrega un enlace a mi perfil de GitHub"

Cada vez que genere código, **revísalo antes de aceptar**.

---

**¡Felicidades!** Ya sabes crear HTML desde cero, publicarlo en internet, y usar IA para ayudarte. Estás listo para proyectos más grandes.
