# Introducción

### console.log()

Es una funciona que imprime por la consola del navegador lo que ingresamos.

```js
console.log("Hola loca")
```

![1687272573905](image/introduccion/1687272573905.png)

Ademas de eso el codigo 'console.log()' puede recibir mas de un parametro, que dan como resultado la concatenacion de los valores ingresados.

```js
console.log('Hola', 'Mundo', '!')
console.log('FELIZ', 'AÑO', 'NUEVO', 2020)
console.log('Bienvenido', 'a', 30, 'Días', 'de', 'JavaScript')
```

### Comentarios

Los comentarios sirven para documentar el codigo en partes clave, donde no quede claro una pedaso de codigo, se recomeinda no usar mucho los comentarios.

```js
// este es un comentario de una linea
console.log("Hola_1")

/*
Este es un comentario de varias lineas
*/
console.log("Hola_2")
```

### Incluir JS en una Pagina web

#### En linea

Podemos incluir codigo js en el mismo archivo .html, esta forma dice que incluiremos el codigo en la etiqueta html.

```html
<!DOCTYPE html>
  <html>
   <head>
     <title>30DíasDeJS:Inline Script</title>
   </head>

   <body>
     <button onclick="alert('Bienvenido a 30DaysOfJavaScript!')">Hazme Click</button>
   </body>
</html>
```

#### Script Interno

Un script interno se declara en el head en la etiqueta script, aunque es mas recomendable declarar la etiqueta script en el body.

```html
<!DOCTYPE html>
<html>
    <head>
    <title>30DíasDeJS:Scripts Internos</title>
    </head>
    <body>
	<button onclick="alert('Bienvenido a 30DaysOfJavaScript!');">Click Me</button>
	<script>
        	console.log("Bienvenido a 30DaysOfJavaScript!")
		// mas codigo js ...
    	</script>
    </body>
</html>
```

#### Script Externo