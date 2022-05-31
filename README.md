Emmanuel Perez - Desafío Objeto Process
-------------------------------------------------------------

Antes de ejecutar la aplicación, 

1. Levantar un servidor local mongoDB en una carpeta a elección (o utilizar una base online).

2. Crear base de datos de nombre ecommerce en el servidor mongodb (use ecommerce)

3. Ingrese en la terminal, ubicado en el directorio del proyecto, el comando:

- npm start

Si desea ingresar por terminal un número de puerto personalizado (mediante minimist), ingrese:

- npm start -p <PORT>


A través del navegador, acceder a las rutas (reemplace <PORT> por el número de Puerto utilizado (por defecto 8080)):

- localhost:<PORT>/info

- localhost:<PORT>/api/randoms

- localhost:<PORT>/login

- localhost:<PORT>/registrar

- localhost:<PORT>/api/productos-test (productos generados con faker)

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