Emmanuel Perez - Desafío Inicio de Sesión
-------------------------------------------------------------

Antes de ejecutar la aplicación, 

1. Levantar un servidor local mongoDB en una carpeta a elección.

2. Crear base de datos de nombre ecommerce en el servidor mongodb (use ecommerce)

3. Ingrese en la terminal, ubicado en el directorio del proyecto, el comando:

- npm start


A través del navegador, acceder a las rutas:

- localhost:8080/login

- localhost:8080/registrar

- localhost:8080/api/productos-test (productos generados con faker)

------------------------------------------------------------------------


La aplicación se conecta a una base de datos de nombre "ecommerce" en un servidor local de Mongo DB.

URL: 'mongodb://localhost:27017/ecommerce'

Para conectar a otra base de datos Mongo:

En el archivo /index.js, reemplazar la URL de Mongo localhost por la URL correspondiente en las líneas 17 y 37.

Las colecciones son users, mensajes, productos.



--------------------------------------------------------------

Dependencias utilizadas: 

    bcrypt,

    connect-mongo,

    ejs,

    express,

    express-session,

    faker,

    mongoose,

    normalizr,
    
    passport,

    passport-local,

    socket.io

*----------------------- Mayo - 2022 --------------------------*