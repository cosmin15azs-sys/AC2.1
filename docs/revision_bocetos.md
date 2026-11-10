# Revisión de bocetos

**Revisor:** Piera (Compañera de clase)

**Fecha de revisión:** 10 de noviembre de 2026

Se entregaron los bocetos digitales al revisor y se le pidió que intentara completar tres tareas sin indicarle qué camino seguir ni dónde pulsar.

| Tarea | Qué entendió o intentó hacer | Dificultad detectada | Cambio propuesto |
| :--- | :--- | :--- | :--- |
| **1. Encontrar un elemento del catálogo y consultar sus características** | Localizó rápidamente la cuadrícula de pistas y señaló el botón de la primera tarjeta de "Fútbol Sala". | En el boceto de la tarjeta no quedaba claro si la acción directa era reservar inmediatamente o ver más datos. | Modificar el texto del botón ("Elegir") por ("Ver detalles") para que no quede ambiguo. |
| **2. Localizar la selección o carrito e identificar cómo continuar** | Identificó la página resumen por los precios desglosados y el total, localizando bien el botón ("COMPLETAR SOLICITUD DE RESERVA") para continuar. | En la cabecera buscaba un icono de un carrito de compra clásico (🛒), lo cual le generó una leve duda inicial. | Cambiar el texto del enlace de navegación principal de "Carrito" a "Mi Reserva". |
| **3. Localizar el formulario y comprender qué información debe introducir** | Leyó los tres bloques (Datos Personales, Reserva, Confirmación) y comprendió fácilmente cómo deben completarse los campos obligatorios. | Dudó en el campo de "Fecha de reserva" sobre qué formato debía escribir (DD/MM/AAAA) al ser un campo vacío sin ninguna sugerencia de formato (por ejemplo un placeholder). | Asegurar que en el desarrollo se utilice un campo con formato de calendario nativo o se incluyan sugerencias/instrucciones. |

### Decisiones de diseño (Cambios incorporados y descartados)

*   **Aceptado:** Cambiar la nomenclatura de "Carrito" a "Mi Reserva" en toda la interfaz. Se incorpora porque en el contexto de un polideportivo municipal se gestionan reservas de espacios, no compras de productos físicos. Esto mejora la coherencia y evita confundir al usuario.
*   **Aceptado:** Utilizar un control de tipo fecha (`<input type="date">`) en el formulario de inscripción en lugar de un campo de texto libre. Se incorpora porque soluciona la duda del formato detectada en la revisión, previniendo errores de validación por parte del usuario.
*   **Descartado:** Añadir un icono visual de un carrito de supermercado en la barra de navegación. Se descarta porque, aunque es un estándar en comercio electrónico, en nuestra temática de alquiler deportivo puede resultar fuera de lugar. Un enlace de texto claro ("Mi Reserva") resulta más preciso y fácil de localizar.