# Control de Uniformes Pro

Sistema de gestión y consulta de inventario de uniformes para equipos deportivos. Permite el seguimiento de tallas, números de camiseta y datos de contacto de los integrantes.

## 🚀 Funcionalidades

- **Búsqueda en tiempo real**: Filtrado instantáneo conforme se escribe en el buscador.
- **Validación de ID**: Sistema de alertas para búsquedas numéricas fuera del rango permitido (1 a 22).
- **Visualización de correos**: Ajuste automático de texto para garantizar que las direcciones de correo sean siempre legibles.
- **Interfaz Móvil**: Optimizado para su uso en campo desde smartphones y tablets.

## 🛠️ Tecnologías utilizadas

- **HTML5**: Estructura semántica de datos.
- **CSS3**: Diseño basado en variables nativas (`:root`) y Flexbox.
- **JavaScript (Vanilla)**: Lógica de filtrado, manipulación del DOM y validación de datos sin dependencias externas.

## 📋 Estructura de la Tabla

El sistema organiza la información en las siguientes columnas:
1. **ID**: Identificador único del jugador.
2. **Nombre Completo**: Nombre registrado en la base de datos.
3. **# Camiseta**: Número asignado para la indumentaria.
4. **Correo Electrónico**: Contacto oficial (con soporte para nombres largos).
5. **Talla Camisa**: Medida de la parte superior (M, L, XL).
6. **Talla Pantaloneta**: Medida de la parte inferior.
7. **Apodo**: Nombre o seudónimo personalizado para la prenda.

## ⚖️ Licencia

Este programa es software libre: usted puede redistribuirlo y/o modificarlo bajo los términos de la **Licencia Pública General de GNU (GNU GPL)** publicada por la Free Software Foundation, ya sea la versión 3 de la Licencia, o (a su elección) cualquier versión posterior.

Este programa se distribuye con la esperanza de que sea útil, pero SIN NINGUNA GARANTÍA; incluso sin la garantía implícita de MERCANTIBILIDAD o APTITUD PARA UN PROPÓSITO PARTICULAR. Consulte la Licencia Pública General de GNU para más detalles.

---
**Desarrollado para el control eficiente de dotaciones deportivas.**


//Instrucciones de mantenimiento:

Para agregar más jugadores: Solo debes insertar una nueva fila (<tr) en el (tbody>) y actualizar el número máximo en la función filtrarYResaltar() dentro de la condición (numID < 1 || numID > 22).