# Sorteo de Amigos

Este es un pequeño proyecto en JavaScript que permite a los usuarios agregar nombres de amigos a una lista y luego seleccionar uno al azar mediante un sorteo.
El objetivo principal de este desafío es fortalecer las habilidades en lógica de programación.

## Funcionalidades

1. **Agregar Amigos**: Permite al usuario ingresar nombres de amigos en un campo de texto y agregarlos a una lista.
2. **Renderizar Lista**: Muestra la lista de amigos agregados en una lista desordenada (`<ul>`) en la interfaz de usuario.
3. **Sortear Amigo**: Selecciona un amigo al azar de la lista y muestra el resultado en la pantalla.

## Cómo funciona

### Agregar Amigos
- El usuario ingresa un nombre en el campo de texto y presiona el botón "Agregar".
- Si el campo está vacío, se muestra una alerta pidiendo que ingrese un nombre.
- Si el nombre es válido, se agrega a la lista `amigo` y se actualiza la interfaz para mostrar el nuevo amigo en la lista.

### Renderizar Lista
- Cada vez que se agrega un nuevo amigo, la función `renderizarAmigos()` recorre la lista `amigo` y crea un elemento `<li>` por cada nombre, que luego se añade a la lista desordenada (`<ul>`) en el HTML.

### Sortear Amigo
- Al presionar el botón "Sortear", se selecciona un nombre al azar de la lista `amigo` utilizando `Math.random()`.
- El nombre seleccionado se muestra en la pantalla y la lista de amigos se limpia para prepararse para un nuevo sorteo.

## Código

El código consta de tres funciones principales:

1. **agregarAmigo()**: Agrega un nombre a la lista `amigo` y actualiza la interfaz.
2. **renderizarAmigos()**: Muestra la lista de amigos en la interfaz.
3. **sortearAmigo()**: Selecciona un amigo al azar y muestra el resultado.
