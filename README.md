# Polideportivo Tres Cantos - Reserva de Pistas

**Descripción:**  
Proyecto web para el módulo de Diseño de Interfaces Web (DIW). Consiste en un catálogo de un espacio deportivo municipal donde los usuarios pueden explorar instalaciones (fútbol sala, pádel, natación, etc.) y realizar solicitudes de reserva.

## Enlace a la web publicada
🔗 [Visitar la web publicada](https://cosmin15azs-sys.github.io/AC2.1/index.html) *(version 1.0)*.

## Páginas disponibles y recorrido recomendado
El recorrido principal diseñado para la tarea es el siguiente:
1. **Inicio (`index.html`)**: Presentación y llamada a la acción principal.
2. **Catálogo (`catalogo.html`)**: Muestra las pistas disponibles en formato cuadrícula.
3. **Detalle (`detalle.html`)**: Accesible pulsando el botón "Ver detalles" en la pista de Fútbol Sala.
4. **Mi Selección (`carrito.html`)**: Resumen de la reserva tras pulsar "Añadir a mi selección".
5. **Formulario (`formulario.html`)**: Pantalla final para solicitar la reserva.
*   *Página adicional*: **Acceso (`login.html`)**, accesible en cualquier momento desde la navegación.

## Instrucciones para abrir el proyecto localmente
Para visualizar la web en un ordenador sin usar GitHub Pages:
1. Descarga el repositorio en formato ZIP o clónalo mediante Git.
2. Descomprime la carpeta (si descargaste el archivo ZIP).
3. Haz doble clic en el archivo `index.html` situado en la raíz para abrirlo directamente en cualquier navegador web.

## Funciones representadas pero no implementadas (Prototipo)
Tal y como requiere la práctica, la interfaz es un prototipo visual. Las siguientes funciones están simuladas:
*   **Acceso de usuarios:** No hay autenticación real ni validación de credenciales.
*   **Filtros y Búsqueda:** Los controles del catálogo existen para evaluar su accesibilidad, pero no modifican los resultados mostrados.
*   **Carrito:** La suma total y la eliminación de elementos son representaciones estáticas HTML.
*   **Envío del formulario:** Los datos no se almacenan ni se envían a ninguna base de datos; la validación es puramente front-end nativa y el envío simula la acción.

## Uso de Flexbox y Grid
*   **Flexbox:** Se ha utilizado en la cabecera (`<header>`) para alinear de forma adaptable el logotipo y la navegación, y en las filas del resumen de reserva (`.fila-carrito`) para separar los elementos del importe.
*   **CSS Grid:** Se ha utilizado en la página del catálogo (`.catalogo-grid`) para crear una cuadrícula responsiva que distribuye las tarjetas de las diferentes instalaciones deportivas.

## Documentación de diseño y comprobación
Toda la documentación de análisis previo y evaluación se encuentra en la carpeta `docs/`:
*   [Definición del proyecto (Propósito, usuarios, contexto y tareas)](docs/definicion.md)
*   [Bocetos de la interfaz](docs/bocetos.md)
*   [Revisión de usabilidad con compañero](docs/revision_bocetos.md)
*   [Revisión con DevTools(F12)](docs/dev_tools.md)
*   [Prueba final de usabilidad con compañero](docs/prueba_final.md)
*   [Revisión de accesibilidad](docs/accesibilidad.md)




## Procedencia de recursos
*   Tipografía: Fuentes estándar del sistema (Arial, sans-serif).
*   Imágenes: Fotos gratuitas descargadas de sitios como Unsplash o Pexels.

## Herramientas de IA utilizadas
*   **Gemini:** Utilizado como asistente de programación para maquetar el HTML semántico, generar la estructura del CSS (distribución con Grid y Flexbox) asegurando que se cumplen los requisitos 
de Desarrollo de interfaces (RA2), Accesibilidad (RA5) y Usabilidad (RA6).
*   **GitHub Copilot (VS Code):** Utilizado para la optimización de código en tiempo real. Facilitó la prevención de errores estructurales mediante sugerencias predictivas y sirvió de apoyo para resolver bloqueos de lógica durante la fase de desarrollo.