# band_names

A new Flutter project.

## Getting Started

# Section3

Aquí tocaremos temas sobre:

- Crear un backend en Node 

- Crear directorios públicos
  
- Variables de entorno
  
- Configuración de Socket.io
  
- Emitir y escuchar eventos
  
- Separar la lógica en diferentes archivos
  
- Realizar respaldos en GitHub
  
- Procedimiento para escuchar cuando un cliente se conecta y se desconecta.
  
- Espero que sea de mucho interés para todo ustedes!

node index.js en la terminal para correr nuestro backend.

sudo npm i -g nodemon para instalar nodemon
nodemon index - para correr el servidor

npm i dotenv

Ajustamos el archivo package.json con lo siguiente:
"scripts": {
"test": "echo \"Error: no test specified\" && exit 1",
"start": "node index.js",
"start:dev": "nodemon index.js"
},
y después podemos utilizar en la terminal sea npm start o sea npm run start:dev

# Section 4

En esta sección tocaremos los siguientes temas:

- Conectarnos a nuestro socket server

- Escuchar y emitir eventos desde y hacia Flutter

- Indicadores visuales del estado de la conexión

- Re-conexión al socket server

- CRUD basado en Sockets

- Gráficas en tiempo real

