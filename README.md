# mongo-store-test

Pequeña aplicación para ver como funciona passport sobre mongo (mongoose) como session store para la autenticación de usuarios.

1. Clone este repo `git clone https://github.com/sposmen/mongo-store-test.git` e ingresa al directorio del clone.
2. `npm install`
3. `mongod --config mongo/mongod.conf` (Inicia en el puerto 27500)
4. `npm start`
5. Cargar el server en http://localhost:3333

[Basado en el ejemplo de passport.](https://github.com/passport/express-4.x-local-example)