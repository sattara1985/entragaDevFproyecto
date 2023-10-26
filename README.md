# Gestión de Empleados

## Descripción

Este proyecto consta de dos partes: el frontend y el backend, diseñados para gestionar empleados. El frontend está construido en React y se encarga de proporcionar una interfaz de usuario para registrar, editar y eliminar empleados. El backend se basa en Node.js y Express, junto con una base de datos MySQL, para proporcionar una API que admite operaciones CRUD en la lista de empleados.
> Pueden Acceder al siguiente enlace para revisar el video del aplicativo funcionando correctamente.Pueden Acceder al siguiente enlace para revisar el video del aplicativo funcionando correctamente.
[Ver VIdeo.](https://youtu.be/OeC9m9jdk_s "Ver VIdeo.")
 
https://youtu.be/OeC9m9jdk_s
 
[![Pantalla Principal](https://github.com/sattara1985/entragaDevFproyecto/blob/main/client/public/pantalla1.png?raw=true "Pantalla Principal")](https://github.com/sattara1985/entragaDevFproyecto/blob/main/client/public/pantalla1.png?raw=true "Pantalla Principal")

## Frontend
https://contacts-backend-d9ar.onrender.com

El [frontend](https://contacts-backend-d9ar.onrender.com "frontend") de la aplicación se encuentra en el archivo `App.js` y es responsable de la interfaz de usuario y la interacción con el usuario. Permite realizar las siguientes acciones:

- Registrar un nuevo empleado.
- Editar detalles de un empleado existente.
- Eliminar un empleado.
- Mostrar la lista de empleados registrados.

Tiene un diseñor responsive por medio de[ Bootstrap](https://getbootstrap.com " Bootstrap") con botones y deseño atractivo al usuario además de un diseño muy intuitivo.

## Backend

https://contacts-backend-d9ar.onrender.com

El[ backend ](https://contacts-backend-d9ar.onrender.com " backend ")de la aplicación se encuentra en el archivo `app.js` y es el servidor de la aplicación. Utiliza Express para crear una API que gestiona las solicitudes del frontend y se conecta a una base de datos MySQL. Proporciona los siguientes endpoints:


| EndPoints | Description                    |
| ------------- | ------------------------------ |
| `POST /create`      | **Crea un nuevo empleado en la base de datos.**       |
| `GET /empleados`   | **Recupera la lista de empleados desde la base de datos.**     |
| `PUT /update/:id`   | **Actualiza los detalles de un empleado existente.**     |
| `DELETE /delete/:id*`   | **Elimina un empleado según su ID.**     |


## Requisitos _

### Frontend

- [Node.js](https://nodejs.org/)
- [React](https://reactjs.org/)
- [Axios](https://axios-http.com/)
- [Bootstrap](https://getbootstrap.com/)
- [SweetAlert2](https://sweetalert2.github.io/)

### Backend

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MySQL](https://www.mysql.com/)
- [CORS](https://expressjs.com/en/resources/middleware/cors.html)

## Instalación

### Frontend

1. Navega al directorio del frontend:

    	bash
		cd frontend
		
1. Instala las dependencias necesarias:

    	npm install
		
1. Inicia la aplicación:

    		npm start

> ***La aplicación estará disponible en http://localhost:3000.***



### Backend

1. Navega al directorio del backend:

    	bash
		cd backend
		
1. Instala las dependencias necesarias:
		npm install

1. Configura la base de datos MySQL: Asegúrate de tener una base de datos MySQL configurada con el nombre "empleados_crud" y los detalles de acceso correspondientes. Puedes configurar la conexión en el archivo app.js.

[![Base de Datos](https://github.com/sattara1985/entragaDevFproyecto/blob/main/client/public/BDREADME.png?raw=true "Base de Datos")](https://github.com/sattara1985/entragaDevFproyecto/blob/main/client/public/BDREADME.png?raw=true "Base de Datos")


4. Inicia el servidor:

		node app.js

> ***El servidor estará disponible en http://localhost:3001.***



### Uso

- El frontend permite interactuar con la aplicación y realizar operaciones en la lista de empleados. CRUD completo con avisos interactivos para el usuario.

[![alertas](https://github.com/sattara1985/entragaDevFproyecto/blob/main/client/public/SWEETALERT.png?raw=true "alertas")](https://github.com/sattara1985/entragaDevFproyecto/blob/main/client/public/SWEETALERT.png?raw=true "alertas")

- El backend proporciona una API REST que maneja las solicitudes del frontend y realiza operaciones en la base de datos.

- Control de errores. Fallo Conexion con la Bd

[![Fallo Conexion](https://github.com/sattara1985/entragaDevFproyecto/blob/main/client/public/falloeliminar.png?raw=true "Fallo Conexion")](https://github.com/sattara1985/entragaDevFproyecto/blob/main/client/public/falloeliminar.png?raw=true "Fallo Conexion")


------------




# Contribución

------------

Si deseas contribuir a este proyecto, sigue estos pasos:

1. Haz un fork del repositorio del frontend o del backend, según donde desees contribuir.
2. Crea una rama para tu contribución: git checkout -b mi-contribucion.
3. Realiza tus cambios y documenta los cambios si es necesario.
4. Haz un commit de tus cambios: git commit -m "Añadido nuevo feature".
5. Sube tus cambios a tu fork: git push origin mi-contribucion.
6. Crea un Pull Request en el repositorio original.


------------


------------

## Agradecimientos

Quiero gradecer a[ Colsubsidio](https://www.colsubsidio.com/ " Colsubsidio"), [Protalento](https://www.protalento.com/ "Protalento"), [DEV.F ](https://new.devf.la/ "DEV.F ")por la oportunidad de poder adquirir todos estos nuevos conocimientos. A mis tutores Mali y Sebastian.



## Ñapa - Adicional

------------

------------
Link de aplicacion que consume una API de carreras.
https://apex.oracle.com/pls/apex/r/sattara1985/races-f1/home?session=110666128930358

------------
