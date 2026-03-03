# Control de Versiones - Catálogo Aziru

## v1.5 - 2026-03-03
- **Mejoras de Diseño y Usabilidad:**
    - Se añadió un marco visible a las tarjetas de producto cambiando el color de fondo de la página para mejorar el contraste y la estética.
    - Se ajustó el ancho del catálogo y se implementó una cuadrícula de 4 columnas en pantallas grandes para una vista más compacta.
    - Se redujo la altura de las imágenes de producto para optimizar el espacio vertical.
- **Gestión de Productos Mejorada:**
    - Se introdujo una propiedad `sortOrder` para permitir un control manual y sencillo del orden de visualización de los productos.
    - Se reorganizó la lista `allProducts` en el código fuente (agrupada por disponibilidad y ordenada por ID) para facilitar futuras ediciones.
- **Actualización de Contenido:**
    - Se añadieron los nuevos productos: "Cuellero Reto las Civilizaciones" y "Jersey Tricolor 2026".
    - Se actualizó el número de contacto de WhatsApp a `3203208173` en todos los botones de compra y consulta.

## v1.4 - 2026-01-29
- **Precios Dinámicos para Licras:** Se implementó un selector en la vista de detalle para que los clientes puedan elegir el tipo de badana (con/sin costuras) y la duración en horas, actualizando el precio del producto automáticamente.
- **Reorganización del Catálogo:** Se reordenaron los productos para dar prioridad a la colección más reciente. El "Jersey Tricolor 2026" ahora aparece primero, seguido por todos los productos de 2025.
- **Nueva Sección "Colecciones Anteriores":** Las prendas de temporadas pasadas (sin año en el nombre) se agruparon en una sección separada al final de la página.
- **Estado "No Disponible":** Las prendas de colecciones anteriores ahora se marcan visualmente como "No Disponible" y se ha desactivado su botón de compra.
- **Filtros por Categoría:** Se añadió una barra de botones para filtrar los productos por tipo de prenda (Jersey, Licra, Chaqueta, etc.). El filtro aplica tanto a la colección principal como a las colecciones anteriores.
- **Actualizaciones Generales:**
    - Se actualizó el precio de todos los "Cuelleros" a $16.000.
    - Se renombró "Tricolor 2026" a "Jersey Tricolor 2026" para consistencia.
    - Se actualizó el número de contacto de WhatsApp en todos los botones de compra al `3232937476`.

## v1.3 - 2024-05-21 (Actual)
- Ajuste: Imágenes en "object-contain" para evitar recortes.
- Ajuste: Eliminación de bordes grises en marcos de fotos.
- Mejora: Modal scrolleable con descripción en lista de guiones (-).
- Estado: FUNCIONA (Estética final aprobada).

## v1.2 - 2024-05-20
- Cambio: Se intentó usar miniaturas, pero se veían borrosas.
- Error: El modal no permitía ver la descripción en pantallas pequeñas.
- Estado: DESCARTADA (Problemas de nitidez).

## v1.1 - 2024-05-20
- Cambio: Implementación de carrusel horizontal en modal.
- Estado: FUNCIONA.
