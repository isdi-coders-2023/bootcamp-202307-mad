# Week 7 - Challenge 2

## API REST Things I already know / Lo que queráis (III)

Continuamos el API REST del Challenge anterior, que se conecte a un fichero JSON, para manipular recursos de tipo _cosas que ya sé_ (o cualquier otro).

Recordemos que el JSON tendrá una sola propiedad de tipo array, donde almacenarán objetos que representarán cosas que hemos aprendido en el bootcamp (o cualquier otro modelo).

Añadimos un segundo endpoint de Films (o lo que quieras) con un repo que conecta con MongoDB usando Mongoose

- El modelo de datos estará representado como "entity" en una carpeta/fichero independiente.
- El repositorio y el controller son clases que se instancian en el Router.
- El interface del repositorio se inyecta en el controller (inversión de dependencias).
- Les errores se controlan mediante un middleware de errores.

Se testa el 100% del backend completo: Things & Films.

Se publica en Render (https://render.com/)
