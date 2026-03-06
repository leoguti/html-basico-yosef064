# Tarea 6 - Reto: Página de horario con estilo (usando Copilot)

## El reto

Crea un archivo llamado **`mi-horario.html`** que muestre tu horario de clases real de esta semana, con colores y estilo visual.

**Regla:** Usa Copilot para ayudarte. Hacer esto a mano tomaría mucho tiempo.

## Requisitos (todos son obligatorios)

Tu página debe tener:

1. **Tu nombre** en un título `<h1>`
2. **Una tabla** con tu horario real de lunes a viernes
3. **Columnas:** Hora, Lunes, Martes, Miércoles, Jueves, Viernes
4. **Al menos 5 filas** con materias reales
5. **Colores diferentes** para cada materia (esto requiere CSS, pídele a Copilot que lo haga)
6. **Un pie de página** que diga: "Hecho con HTML + Copilot | Escuela OSM Salesiano 2026"

## Cómo hacerlo

1. Abre tu repositorio en github.dev (presiona `.` en tu repo)
2. Abre el chat de Copilot
3. Pídele algo como:

```
Crea una página HTML llamada mi-horario.html con mi horario de clases.
Quiero una tabla de lunes a viernes con las horas de 7am a 1pm.
Cada materia debe tener un color de fondo diferente.
Usa CSS para que se vea bonito.
Mi nombre es [TU NOMBRE] y estudio en el Colegio Salesiano de Duitama.
Agrega un pie de página que diga "Hecho con HTML + Copilot | Escuela OSM Salesiano 2026"
```

4. **Revisa el código que genera.** Deberías reconocer:
   - `<table>`, `<tr>`, `<td>`, `<th>` (los aprendiste en la Tarea 5)
   - `<style>` (esto es CSS, es nuevo. Controla los colores y el diseño)
   - `background-color` (el color de fondo de cada celda)

5. **Cambia los datos de ejemplo** por tu horario real
6. Haz commit con mensaje: `Crear horario con Copilot`

## Verificar

Abre tu página en GitHub Pages:
```
https://leoguti.github.io/html-basico-[TU-USUARIO]/mi-horario.html
```

Debería verse como una tabla de colores con tu horario.

## Agregar enlace en tu index.html

Edita tu `index.html` y agrega un enlace a tu nueva página:

```html
<li><a href="mi-horario.html">Mi horario de clases</a></li>
```

Commit con mensaje: `Agregar enlace a mi horario`

## ¿Qué aprendiste?

- Copilot puede generar páginas complejas en segundos
- Tú **verificas** que el resultado sea correcto
- CSS controla los colores y el estilo visual (lo veremos más a fondo después)
- Siempre personaliza lo que la IA genera: los datos deben ser **tuyos**
