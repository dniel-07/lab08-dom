# Bitacora de JavaScript interactivo
 
Laboratorio 08: JavaScript Interactivo - DOM, Eventos y Objetos.
Navegador usado: (escribe aqui cual usaste)
 
## Ejercicio 2: Seleccionar y modificar el DOM

| Instruccion | Que cambio en la pantalla | Se mantiene al recargar (Si/No) |
|-------------|---------------------------|---------------------------------|
| textContent desde la consola | El título cambió a “Hola desde la consola”. | No |
| textContent desde app.js | 	
El título cambió a “Hola TECSUP”. | Sí |
| style.color | El título se puso de color azul. | Sí |
| classList.add | El párrafo obtuvo un fondo amarillo. | Sí |
| createElement + appendChild | Se agregó “JavaScript” a la lista junto a HTML y CSS. | Sí |
 
## Ejercicio 3: Evento click

 | Tipo de evento | Que accion lo dispara | Cuanto suma por accion |
|----------------|-----------------------|------------------------|
| click | Hacer un clic en el botón “Sumar 1”. | 1 |
| dblclick | Hacer doble clic en el botón “Sumar 1”. | 1 por cada doble clic |
| mouseover | Pasar el cursor sobre el botón “Sumar 1”. | 1 por cada vez que se activa el evento |

## Ejercicio 4: Eventos input y submit

| Prueba | Que paso en la pantalla | Se recargo la pagina (Si/No) |
|--------|-------------------------|------------------------------|
| Escribir en el campo nombre | 	
El saludo cambió mientras escribía, mostrando “Hola, ” seguido del nombre ingresado. | No |
| Enviar sin preventDefault | Apareció el mensaje “Enviado: correo”, pero desapareció al recargarse la página. | Sí |
| Enviar con preventDefault, correo sin @ | 	
Apareció el mensaje “Correo no valido: falta @” en rojo. | No |
| Enviar con preventDefault, correo con @ | 	
Apareció el mensaje “Enviado:” seguido del correo ingresado. | No |
 
## Ejercicio 5: Clases y objetos

 | Objeto | nombre | precio | descripcion() | conDescuento(0.25) |
|--------|--------|--------|---------------|--------------------|
| laptop | 	Laptop |  2500| Laptop - S/ 2500.00 |  1875 |
| mouse | Mouse | 45 | Mouse - S/ 45.00 | 33.75 |
| teclado | Teclado | 120 | Teclado - S/ 120.00 | 90 |
| monitor | Monitor | 680 | Monitor - S/ 680.00 | 510 |

## Ejercicio 6: DOM, eventos y objetos juntos

| Prueba | Total que muestra la pagina | Correcto (Si/No) |
|--------|-----------------------------|------------------|
| Cuaderno 12.50 | S/ 12.50 | Sí |
| + Lapicero 3.20 | S/ 15.70 | Sí |
| + Mochila 89.90 | S/ 105.60 | Sí |
| Sin Number() | No se actualiza correctamente; aparece un error en la consola. | No |
 
| Pieza | Linea de tu codigo donde aparece | Para que sirve |
|-------|----------------------------------|----------------|
| DOM | document.querySelector("#total") | Selecciona el elemento HTML donde se muestra el total del carrito. |
| Evento | formProducto.addEventListener("submit", (evento) => { ... }) | Ejecuta el código cuando se envía el formulario para agregar un producto. |
| Objeto | const producto = new Producto(prodNombre.value, Number(prodPrecio.value)); | Crea un objeto producto con el nombre y el precio ingresados. |

- [Bitacora de JavaScript interactivo](notas/BITACORA.md)
- [Ver la pagina en vivo](https://TU-USUARIO.github.io/lab08-dom/)