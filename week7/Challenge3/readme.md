# Week 7 - Challenge 2

## API REST Things I already know / Lo que queráis (IV)

Continuamos el API REST del Challenge anterior, que:

- se conecte a un fichero JSON, para manipular recursos de tipo _cosas que ya sé_ (o cualquier otro).
- un segundo endpoint de Films (??) utiliza un repo que conecta con MongoDB usando Mongoose

Añadimos **Users** relacionándolo con Films (??)

- El modelo de datos estará representado como "entity" en una carpeta/fichero independiente.
- Las rutas son /register y /login
- El repositorio y el controller son clases que se instancian en el Router.
- El interface del repositorio se inyecta en el controller (inversión de dependencias).
- Les errores se controlan mediante un middleware de errores.

**/register** registra usuarios
**/login** comprueba el login y si es correcto devuelve los datos del usuario (sin token)

Actualizamos [Post] /Films (??) -> **create Films (??)**

Se testa el 100% del backend completo: Things & Films & User & All.

Se publica en Render (https://render.com/)
