# Comprobación de Accesibilidad (RA5)

| Aspecto | Página o elemento revisado | Método utilizado | Resultado / Corrección |
| :--- | :--- | :--- | :--- |
| **Estructura** | Todas las páginas (`index.html`...) | Revisión de código HTML | **Correcto.** Atributo `lang="es"` incluido. Títulos `<title>` descriptivos por página y jerarquía `<h1>`, `<h2>` respetada en main. |
| **Imágenes** | `catalogo.html`, `detalle.html` | Revisión de código HTML | **Correcto.** Todas las imágenes tienen el atributo `alt` describiendo la pista (ej. `alt="Pista exterior de Fútbol Sala"`). |
| **Formularios** | `formulario.html` | Inspección visual y código | **Correcto.** Etiquetas `<label>` asociadas con `for` al `id` del input. Agrupación comprensible con `<fieldset>` y `<legend>`. |
| **Teclado / Foco** | `formulario.html`, navegación | Tabulador en el navegador | **Correcto.** El foco sigue un recorrido lógico (de arriba a abajo, izquierda a derecha). Se implementó `*:focus-visible { outline: 3px solid var(--color-foco); }` para destacar el elemento activo. |
| **Contraste** | Textos y botones | Herramienta de contraste | **Correcto.** Botones `#0056b3` sobre texto blanco (ratio > 4.5:1). Texto principal `#333333` sobre fondo blanco, superando el estándar AA. |
| **Uso del color** | `carrito.html`, validaciones | Inspección visual | **Correcto.** La información no depende solo del color. En el formulario, los campos requeridos tienen la palabra "(Requerido)" explícita en el label. |
| **Ampliación** | Todas las páginas | Zoom del navegador al 200% | **Correcto.** Al ampliar al 200%, gracias al uso de Grid, Flexbox y `rem`, el texto crece y los contenedores se reajustan sin superponerse ni perder funcionalidad. |