# Tarea 4 - Romper y arreglar (experimento)

## ¿Qué vas a hacer?

Vas a **romper tu código a propósito** para entender qué hace cada parte. Así aprendes cómo funciona HTML de verdad.

## Experimento 1: ¿Qué pasa si quito una etiqueta de cierre?

1. Edita `mi-pagina.html`
2. Busca esta línea:
   ```html
   <h1>Hola, soy TU NOMBRE</h1>
   ```
3. Borra el `</h1>` del final para que quede:
   ```html
   <h1>Hola, soy TU NOMBRE
   ```
4. Haz commit con mensaje: `Experimento: quitar cierre de h1`
5. Abre tu página en GitHub Pages y mira qué pasó

**¿Qué deberías ver?** Todo el texto después se vuelve un título enorme. El `<h1>` no sabe dónde terminar.

6. Ahora **arréglalo**: vuelve a poner el `</h1>` y haz commit con mensaje: `Arreglar: restaurar cierre de h1`

## Experimento 2: ¿Qué pasa si cambio los números del heading?

1. Edita `mi-pagina.html`
2. Cambia un `<h2>` por `<h4>`:
   ```html
   <h4>Sobre mí</h4>
   ```
3. Commit y revisa: ¿qué cambió?

**Resultado:** Los números del 1 al 6 controlan el tamaño:
- `<h1>` = Más grande
- `<h2>` = Grande
- `<h3>` = Mediano
- `<h4>` = Normal-pequeño
- `<h5>` = Pequeño
- `<h6>` = Más pequeño

4. Déjalo como estaba (`<h2>`) y haz commit.

## Experimento 3: ¿Qué pasa si quito el `<body>`?

1. Borra las líneas `<body>` y `</body>` (solo esas dos líneas, no el contenido)
2. Commit y revisa

**Resultado:** ¡Funciona igual! El navegador es inteligente y adivina dónde va el body. Pero es mala práctica no ponerlo.

3. Vuelve a ponerlo y haz commit.

## Experimento 4: Cambiar la etiqueta `<title>`

1. Cambia el texto dentro de `<title>`:
   ```html
   <title>Página de [TU NOMBRE] - Salesiano</title>
   ```
2. Commit y revisa: ¿dónde aparece el cambio?

**Resultado:** El título aparece en la **pestaña** del navegador, no en la página.

## Lo que aprendiste

- Cada etiqueta tiene un propósito
- Si falta el cierre, el navegador se confunde
- El navegador intenta mostrar algo aunque el HTML esté mal, pero el resultado es impredecible
- **Siempre cierra tus etiquetas**

## ¿Listo?

Asegúrate de que tu página quedó **funcionando bien** después de los experimentos. Pasa a la [Tarea 5](tarea-5.md).
