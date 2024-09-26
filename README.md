# Proyecto Integrador: CRUD con Node.js y MySQL

## Descripción del Proyecto

En este proyecto, desarrollarás una aplicación basada en Node.js y MySQL que permita realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) en una base de datos. La base de datos MySQL deberá estar generada en MySQL Workbench y tu aplicación Node.js se conectará a ella.

Deberás usar el dataset JSON proporcionado.

## Datasets Proporcionados

- **trailerflix.json**: Datos de peliculas.

## Funcionalidades del CRUD

1. **Obtener todos los productos**
   - Endpoint para leer todos los productos de la colección.
   - Control de errores para manejar la indisponibilidad de la base de datos.

2. **Obtener un producto**
   - Endpoint para obtener un producto por su ID.
   - Control de errores para manejar casos en que el producto no se encuentre o la base de datos no esté disponible.

3. **Filtrar productos**
   - Endpoint para filtrar productos por nombre (búsqueda parcial).
   - Control de errores para manejar coincidencias no encontradas o problemas de conexión.

4. **Agregar un nuevo producto**
   - Endpoint para agregar un nuevo producto.
   - Validación y control de errores.
   - Generación de un código numérico para el nuevo producto.

5. **Modificar el precio de un producto**
   - Endpoint para cambiar el precio de un producto usando PATCH.
   - Control de errores para manejar problemas durante la actualización.
     
6. **Borrar un producto**
   - Endpoint para borrar un producto usando DELETE.
   - Control de errores para manejar problemas durante el borrado.

7. **Control de errores**
   - Manejo de errores en la estructura de las solicitudes y respuestas.
   - Respuesta adecuada con mensajes y códigos de error específicos.
   - Control de acceso a rutas no existentes con respuestas apropiadas.

## Fechas Importantes

- **Avance del Proyecto**: 10 de octubre de 2024
  - Tener listos los endpoints básicos, el control de rutas inexistentes, la conexión con MySQL y los métodos GET funcionando.

- **Presentación Final**: 24 de octubre de 2024
  - Proyecto 100% funcional.

## Estructura del Repositorio

```plaintext
/json
  - trailerflix.json
/README.md
/app.js
/database.js
/product.js
```

### Descripción de Archivos

- **/json**: Carpeta que contiene los datasets JSON.
- **/README.md**: Archivo con la descripción del proyecto.
- **/app.js**: Archivo principal de la aplicación Node.js donde se define toda la lógica de rutas y la conexión a la base de datos.
- **/database.js**: Archivo para configurar la conexión a la base de datos MongoDB.
- **/product.js**: Archivo que contiene el esquema (schema) del producto utilizando Mongoose.

## Instrucciones de Entrega

1. **Fork** el repositorio desde [aquí](https://github.com/FabioDrizZt/Trabajo-Integrador-Relacional-Backend-Diplomatura-UNTREF/fork).
2. **Clona** tu fork en tu máquina local.
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio-fork.git
   ```
3. Realiza los cambios y sube tu código a tu fork.
4. **Sube** los cambios a tu fork.
   ```bash
   git add .
   git commit -m "Descripción de los cambios"
   git push origin main
   ```

5. Agrega a los siguientes usuarios como colaboradores en tu repositorio:
   - [FabioDrizZt](https://github.com/FabioDrizZt)
   - [JuanNebbia](https://github.com/JuanNebbia)
   - [NKrein](https://github.com/NKrein)
   - [mathiasbarbosa](https://github.com/mathiasbarbosa)

## Conclusión

Este proyecto te permitirá aplicar tus conocimientos en desarrollo backend con Node.js y MySQL, implementando un CRUD completo con control de errores y buenas prácticas. ¡Buena suerte y adelante con el desarrollo!

---

Recuerda mantener tu código limpio, documentado y seguir las buenas prácticas de desarrollo. ¡Nos vemos en clase para revisar tu progreso el 10 de octubre de 2024!
