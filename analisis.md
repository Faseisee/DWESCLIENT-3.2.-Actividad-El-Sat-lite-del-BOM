**1. El objeto window se considera el objeto global del entorno del navegador (BOM). Explica la diferencia entre este y un objeto nativo global del lenguaje JavaScript como Math o JSON. ¿Por qué no hace falta escribir window.Math?**

El objeto `window` pertenece al BOM y representa la ventana del navegador, permitiendo interactuar con sus funcionalidades, como abrir nuevas ventanas, obtener información del navegador e incluso modificar la dirección de una página.

En cambio, `Math` es un objeto nativo de JavaScript, ya que forma parte del propio lenguaje y permite realizar operaciones matemáticas sin depender de las funcionalidades del navegador.

No es necesario escribir `window.Math` porque `Math` es un objeto global de JavaScript y está disponible directamente sin tener que poner `window.` delante.

En este ejemplo, los dos códigos funcionan y devuelven el mismo resultado `(4)`, aunque el primero es la forma correcta de utilizarlo:

- `Math.floor(4.8);`
- `window.Math.floor(4.8);`

**2. Identifica a qué categoría (BOM u objeto nativo de JS) pertenecen las siguientes instrucciones que utilizaremos en la práctica:**

- `window.open()`: Pertenece al BOM porque permite abrir nuevas ventanas en el navegador.
- `parseFloat()`: Es un objeto nativo de JavaScript que permite convertir una cadena de texto en un número decimal.
- `Math.floor()`: Es un objeto nativo de JavaScript y permite redondear un número hacia abajo.
- `navigator.userAgent`: Pertenece al BOM porque permite obtener información sobre el navegador.
