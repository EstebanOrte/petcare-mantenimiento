# Historias de usuario del taller (HU-12 a HU-16)

Estas historias amplían el MVP de PetCare (HU-01 a HU-11). Cada una se implementa en una rama propia y se integra a `main`.

| ID | Historia de usuario | Criterios de aceptación | Rama |
|----|---------------------|-------------------------|------|
| HU-12 | Como **propietario**, quiero buscar un proveedor por el nombre de su negocio, para encontrar rápido un lugar que ya conozco. | El buscador tiene el campo "Nombre del negocio (opcional)". La búsqueda no distingue mayúsculas y funciona junto con el tipo, la localidad y el precio. Si no hay coincidencias, se muestra un mensaje. | `feature/hu-12-buscar-por-nombre` |
| HU-13 | Como **propietario**, quiero escribir indicaciones en cada reserva, para que el proveedor sepa qué necesito en esa cita. | Al reservar hay un campo opcional de hasta 140 caracteres. Las indicaciones se ven en "Mis reservas" y en las solicitudes del proveedor. | `feature/hu-13-indicaciones-reserva` |
| HU-14 | Como **proveedor**, quiero ver cuántas citas confirmadas tengo hoy, para organizar mi jornada. | El panel del proveedor muestra la tarjeta "Citas de hoy: N" con la lista de las citas confirmadas de la fecha actual. | `feature/hu-14-citas-de-hoy` |
| HU-15 | Como **propietario**, quiero calificar de 1 a 5 estrellas un servicio completado, para ayudar a otros a elegir. | Solo las reservas en estado Completada se pueden calificar, una sola vez. Los resultados de búsqueda muestran el promedio y el número de calificaciones del proveedor. | `feature/hu-15-calificar-servicio` |
| HU-16 | Como **propietario**, quiero descargar mis reservas en un archivo CSV, para llevar el control de los gastos de mi mascota. | "Mis reservas" tiene el botón "Descargar CSV". El archivo incluye fecha, hora, proveedor, servicio, mascota, precio, estado, motivo e indicaciones, y abre bien en Excel. | `feature/hu-16-exportar-csv` |
