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

## Paso 1: Abrir el chat de Copilot

1. Ve a **https://github.com/copilot** (abre este enlace directamente)
2. Se abre un chat. Es como hablar con una IA que sabe programar.

**Si no se abre:** Asegúrate de haber hecho el Paso 0 primero.

## Paso 2: Pedir código a Copilot

1. En el chat, escribe esto:

```
Hazme el código HTML para agregar una sección "Mi horario de clases"
con una tabla que tenga las columnas: Día, Materia, Hora.
Agrega 3 filas de ejemplo. Solo dame el código que va dentro del <body>.
```

2. Presiona **Enter** para enviar
3. Copilot va a generar código HTML
4. **Revisa el código antes de usarlo:**
   - ¿Ves etiquetas que conoces? (`<h2>`, `<p>`, etc.)
   - ¿Hay etiquetas nuevas? (probablemente `<table>`, `<tr>`, `<td>`, `<th>`)
   - ¿El contenido tiene sentido?

## Paso 3: Pegar el código en tu página

1. **Copia** el código que Copilot generó (botón de copiar o Ctrl+C)
2. Ve a tu repositorio: https://github.com/leoguti/html-basico-[TU-USUARIO]
3. Abre **mi-pagina.html**
4. Haz clic en el **lápiz** para editar
5. **Pega** el código de Copilot antes del `</body>` (al final del contenido)
6. **Cambia los datos de ejemplo** por los tuyos
7. Commit con mensaje: `Agregar tabla de horario con ayuda de Copilot`

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

## La regla de oro del Vibe Coding

```
La IA escribe código → Tú lo revisas → Tú lo entiendes → Tú lo aceptas o corriges
```

Nunca aceptes código que no entiendas. Siempre pregunta: "¿qué hace esta línea?"

## Paso 5 (Bonus): Pide algo más

Vuelve a https://github.com/copilot y prueba pedirle:
- "Hazme código HTML para un pie de página con la fecha de hoy"
- "Hazme código HTML para cambiar el color del título a azul usando style"
- "Hazme código HTML para un enlace a mi perfil de GitHub"

Cada vez que genere código, **cópialo, pégalo en tu archivo, y revísalo antes de hacer commit**.

---

**¡Felicidades!** Ya sabes crear HTML desde cero, publicarlo en internet, y usar IA para ayudarte. Pasa a la [Tarea 6](tarea-6.md).
