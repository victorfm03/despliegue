En el paso 2 usamos un bind mount para conectar una carpeta de Windows al contenedor.
En el paso 3 usamos un volumen Docker para guardar datos de forma independiente al contenedor.

Para la base de datos de la Biblioteca DES usaríamos un volumen Docker, porque los datos se conservan aunque se elimine el contenedor y son más fáciles de gestionar
