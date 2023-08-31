# Week 7 - Challenge 2

## API REST Things I already know / Lo que queráis (V)

Continuamos el API REST del Challenge anterior, que:

- un endpoint de Films
- un endpoint de Users

Utilizan repos que conecta con MongoDB usando Mongoose

- El modelo de datos estará representado como "entity" en una carpeta/fichero independiente.
- Las rutas son /register y /login
- El repositorio y el controller son clases que se instancian en el Router.
- El interface del repositorio se inyecta en el controller (inversión de dependencias).
- Les errores se controlan mediante un middleware de errores.

/register registra usuarios y **encripta** la password
/login comprueba el login y si es correcto devuelve los datos del usuario y **el token**

Creamos un interceptor para el login y protegemos las rutas de Films

Probamos que funciona desde postman y desde un front

Se testa el 100% del backend completo: Things & Films & User & All.

Se publica en Render (https://render.com/)
