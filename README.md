# Delilah Resto :Api de pedidos
Trabajo número 3 del curso de Desarrollo Web Full Stack de Acámica. 

## Lenguajes y tecnologias 
-Node.js 
-Postman
-XAMPP

- #### Descarga de Node.js
  Pagina oficial de[Node.js](https://nodejs.org/).
  
- #### Comandos de instalación:Ubuntu

  Tipeando: 

      $ sudo apt install nodejs
      $ sudo apt install npm


  Puedes encontrar más información en la página oficial de [NPM](https://npmjs.org/).

Si la instalación es exitosa los siguientes comandos tipeados pueden ser ejecutados.

    $ node --version
    v8.11.3

    $ npm --version
    6.1.0

### Postman y XAMPP
Dirígete a [Postman](https://www.postman.com/downloads/) y sigue las instrucciones de descarga.
Dirígete a [XAMPP](https://www.apachefriends.org/es/index.html) y sigue las instrucciones de descarga.

## Para empezar 
- Clona el repositorio
```
https://github.com/megagringa/DelilahResto.git
```

## Ejecuta
``npm install`` para instalar las dependencias.

### Tablas MySQL
En el archivo ``create_tables.sql`` encontrarás las estructuras de las tablas para la utilización de la API, la creación del administrador en donde el usuario podrá crear, modificar, borrar productos, usuarios y pedidos, y visualizar la información sobre los usuarios y los pedidos realizados.

### Inicio del servidor
- Ejecuta ```node server.js``` en tu consola
- Escribe la dirección en tu navegador ```http://localhost:3000```
- Mensaje * Servidor iniciado *
- Dirígete a Xampp, una vez en el panel de inicio, en la seccion Modules, haz click en los botones ``` start``` de la   fila correspondiente a Apache y MySQL.
- Puedes empezar con las pruebas en Postman.

### Endpoints
Encontrarás los posibles endpoints en el documento ``spec.yaml``. Puedes abrirlo en el [editor de Swagger](https://editor.swagger.io/).

- Para ingresar un pedido

```
{
    "productos" : [{
        "id" : "1"
        "nombre" : "ejemplo1",
        "cantidad" : "5"
    },{
        "id" : "2"
        "nombre" : "ejemplo2",
        "cantidad" : "5"
    }],
    "mododepago" : "Efectivo/tarjeta"
}

```
