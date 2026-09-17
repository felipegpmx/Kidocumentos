# Documentos públicos de Ki Clash

El juego vive en un repositorio privado. Esto es lo único que tiene que ser
público, y está aquí por un motivo concreto: **Google Play exige un enlace a la
política de privacidad que abra de verdad**, lo visita al revisar la ficha, y un
404 es un rechazo. Pages en un repositorio privado es de pago; en uno público,
gratis.

    https://felipegpmx.github.io/Kidocumentos/privacidad.html

## El original está en el juego, no aquí

`privacidad.html` es una **copia** de `public/privacidad.html` del repositorio
del juego, que es donde se edita: el juego también la enseña desde dentro, en
Ajustes, y ahí tiene que salir la misma que ve Play.

Dos copias del mismo texto es exactamente la forma de que un día digan cosas
distintas, así que hay una red: `npm run test:publicacion`, en el repositorio
del juego, guarda la huella de lo que se publicó aquí y se pone en rojo si el
original cambia sin republicar. Cuando eso pase:

1. Copiar `public/privacidad.html` del juego encima de este fichero y empujar.
2. Actualizar la huella en el juego, que la propia prueba te dice cuál es.
3. Abrir la dirección de arriba y comprobar que carga.

## Encender Pages

Una vez, a mano: **Settings › Pages › Build and deployment › Source: GitHub
Actions**. Después se publica solo en cada empujón a `main`.
