# FEPAX_Solutions
## Sistema de Gestión Administrativa para la empresa FEPAX Solutions

Este sistema gestiona el control de inventario y ventas para FEPAX SOLUTIONS, una empresa de ferretería, electrónica y herramientas. 
Proporciona las siguientes funcionalidades: 
* Agregar productos 
* Gestionar almacén
* Realizar ventas
* Generar tickets de las ventas

### Problemática
La empresa carece de un sistema digital centralizado para manejar inventario de los productos, lo que ocasiona errores manuales y dificultad para rastrear las operaciones de venta.

### Solución
Este sistema simplifica la gestión del inventario y ventas mediante una interfaz intuitiva, impresión de tickets, y control centralizado en Java con bases de datos en MySQL.

### Arquitectura 
*MVC* 
1. **MODELO:**
   * Métodos para CRUD (Crear, Leer, Actualizar, Eliminar).
   * Implementación de frameworks ORM como Hibernate o consultas SQL manuales con JDBC.
2. **VISTA:**
   * Formularios para entrada de datos (alta/baja/modificación de productos).
   * Tablas para mostrar inventario y reportes de ventas.
   * Ventanas o páginas para la generación de tickets detallados.
3. **CONTROLADOR:**
   * Validación, control de flujo y llamadas a operaciones del modelo.
   
*CLIENTE*
* Permite acceso desde navegadores.
* Realiza solicitudes HTTP al servidor.

*SERVIDOR*
* Procesar solicitudes CRUD.
* Enviar reportes y datos al cliente.
* Gestionar seguridad y autenticación.

*BASE DE DATOS*
* Almacenar los datos de inventarios, usuarios y ventas.
* Asegurar la integridad de los datos mediante claves foráneas.
* Optimizar la recuperación de datos con índices y consultas SQL.
