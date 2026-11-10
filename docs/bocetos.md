<pre>
   
# Bocetos de la Interfaz (Baja Fidelidad / Estructura)

## 1. Página Inicial (index.html)
Muestra la navegación principal y el botón de llamada a la acción.
+-----------------------------------------------------------+
| POLIDEPORTIVO TRES CANTOS    Inicio | Instalaciones | Login |
+-----------------------------------------------------------+
|                                                           |
|             BIENVENIDO A TU CENTRO DEPORTIVO              |
|                                                           |
|      Descubre nuestras instalaciones, consulta            |
|      disponibilidad y reserva tu pista en pocos pasos.    |
|                                                           |
|                [ VER CATÁLOGO DE PISTAS ]                 |
|                                                           |
+-----------------------------------------------------------+
| (c) 2026 Polideportivo Tres Cantos                        |
+-----------------------------------------------------------+

## 2. Página de Acceso (login.html)
Incluye la advertencia obligatoria de prototipo sin autenticación real.
+-----------------------------------------------------------+
| POLIDEPORTIVO TRES CANTOS    Inicio | Instalaciones       |
+-----------------------------------------------------------+
|                                                           |
|  [!] Aviso: Demostración sin autenticación real           |
|                                                           |
|  +-- Tus credenciales ---------------------------------+  |
|  |                                                     |  |
|  | Correo electrónico: [_____________________________] |  |
|  | Contraseña:         [_____________________________] |  |
|  |                                                     |  |
|  |                   [ ACCEDER ]                       |  |
|  +-----------------------------------------------------+  |
+-----------------------------------------------------------+

## 3. Página de Catálogo (catalogo.html)
Muestra los filtros, el resumen de resultados, el grid de 6 elementos y paginación.
+-----------------------------------------------------------+
| POLIDEPORTIVO TRES CANTOS    Inicio | Carrito             |
+-----------------------------------------------------------+
| Buscar: [_______] Superficie: [v]      [ Aplicar Filtros] |
| Mostrando 1-6 de 18 resultados                            |
|                                                           |
| +-------------+  +-------------+  +-------------+         |
| | [ IMAGEN ]  |  | [ IMAGEN ]  |  | [ IMAGEN ]  |         |
| | F. Sala     |  | F. 7        |  | Pádel       |         |
| | 15€/h       |  | 25€/h       |  | 12€/h       |         |
| | [ Elegir ]  |  | [ No disp ] |  | [ No disp ] |         |
| +-------------+  +-------------+  +-------------+         |
|                                                           |
| +-------------+  +-------------+  +-------------+         |
| | [ IMAGEN ]  |  | [ IMAGEN ]  |  | [ IMAGEN ]  |         |
| | Tenis       |  | Piscina     |  | Atletismo   |         |
| | 10€/h       |  | 4€/sesión   |  | 3€/sesión   |         |
| | [ No disp ] |  | [ No disp ] |  | [ No disp ] |         |
| +-------------+  +-------------+  +-------------+         |
|                                                           |
|           << Anterior | Página 1 | Siguiente >>           |
+-----------------------------------------------------------+

## 4. Página de Detalle (detalle.html)
Muestra imagen, características y la acción principal.
+-----------------------------------------------------------+
| POLIDEPORTIVO TRES CANTOS          < Volver al catálogo   |
+-----------------------------------------------------------+
|                                                           |
|  +--------------+   Pista Fútbol Sala (Césped Artif.)     |
|  |              |                                         |
|  |  [ IMAGEN    |   - Dimensiones: 40x20 metros.          |
|  |   GRANDE ]   |   - Vestuarios incluidos.               |
|  |              |                                         |
|  +--------------+   Tarifa: 15€ / hora                    |
|                                                           |
|                     [ AÑADIR A MI SELECCIÓN ]             |
+-----------------------------------------------------------+

## 5. Página de Carrito / Selección (carrito.html)
Listado de ítems seleccionados, recálculo y control de eliminación.
+-----------------------------------------------------------+
| POLIDEPORTIVO TRES CANTOS          < Seguir explorando    |
+-----------------------------------------------------------+
|  MI SELECCIÓN DE RESERVAS                                 |
|                                                           |
|  Pista Fútbol Sala - 18:00h              15.00€  [ Elim ] |
|  -------------------------------------------------------  |
|  Luz artificial (Extra)                   5.00€  [ Elim ] |
|  =======================================================  |
|  TOTAL ESTIMADO                          20.00€           |
|                                                           |
|           [ COMPLETAR SOLICITUD DE RESERVA ]              |
+-----------------------------------------------------------+

## 6. Página de Formulario (formulario.html)
Formulario agrupado en fieldsets y con controles claramente asociados.
+-----------------------------------------------------------+
| POLIDEPORTIVO TRES CANTOS          < Volver a Mi Selecc.  |
+-----------------------------------------------------------+
|  FORMULARIO DE RESERVA                                    |
|                                                           |
|  +-- Datos Personales ---------------------------------+  |
|  | Nombre completo: [________________________________] |  |
|  | Correo (Req):    [________________________________] |  |
|  | Teléfono:        [_________________]                |  |
|  +-----------------------------------------------------+  |
|                                                           |
|  +-- Detalles de la Reserva ---------------------------+  |
|  | Deporte: [ Fútbol Sala v ]      Fecha: [ ________ ] |  |
|  | Nivel:  (o) Iniciación   ( ) Amateur                |  |
|  | Peticiones especiales:                              |  |
|  | [_________________________________________________] |  |
|  +-----------------------------------------------------+  |
|                                                           |
|  +-- Confirmación -------------------------------------+  |
|  | [X] Acepto las normas de uso (Requerido)            |  |
|  +-----------------------------------------------------+  |
|                                                           |
|                  [ SOLICITAR RESERVA ]                    |
+-----------------------------------------------------------+

</pre>