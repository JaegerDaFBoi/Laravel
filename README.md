# Laravel

**Proyecto basico para aprender Laravel**
Se debe instalar composer https://getcomposer.org/

********

![image](https://user-images.githubusercontent.com/92832390/163894526-b3c9f701-6b35-467d-a8a2-c86174ba56ac.png)
Creacion del proyecto por medio de CMD
********
Con code . se abre directamente el proyecto en VS Code
********
![image](https://user-images.githubusercontent.com/92832390/163894938-2bf9afba-1c7d-4d09-8d96-a1b16c6a6971.png)
Inicializamos el servidor del proyecto.
![image](https://user-images.githubusercontent.com/92832390/163894970-96f38a55-4314-4d92-8512-ccdb4b47a4eb.png)
Se abre el proyecto por medio de este link
********
![image](https://user-images.githubusercontent.com/92832390/163895114-0683c378-7319-4c20-a142-0d727ddaded3.png)
Configuramos el archivo .env para definir la base de datos, información del proyecto. Es el archivo de configuración
********
![image](https://user-images.githubusercontent.com/92832390/163895504-12a009b4-b3a7-49e7-9513-0a993ac191e5.png)
Instalación de Jetstream. Ambiente para frontend en Laravel
Documentacion: https://jetstream.laravel.com/2.x/installation.html
********
![image](https://user-images.githubusercontent.com/92832390/163896434-45f146b4-6518-4bdf-9832-dbe3c59c437e.png)
Instalacion de Jetstream con Livewire en el proyecto 
********
![image](https://user-images.githubusercontent.com/92832390/163897216-792cfae0-1fd3-44d0-9ced-c80f79b30870.png)
Instalacion de las dependencias de Jetstream por npm.
Para usar npm, se debe instalar node.Js
https://nodejs.org/es/
********
![image](https://user-images.githubusercontent.com/92832390/163897615-3bc73a0f-2d2c-4820-a443-5ab21c434e34.png)
Comando para realizar el build de las dependencias y el proyecto al modificarse cualquier CSS
********
![image](https://user-images.githubusercontent.com/92832390/163897889-32ab003b-d44d-46ac-b255-f57651223ae6.png)
Se hace la migración de la base de datos. Se migran las tablas correspondientes de Jetstream para construir un login con registro de usuarios, sesiones, doble factor de autenticacion, etcetera.
********

METODOS CREATE Y SHOW 

![image](https://user-images.githubusercontent.com/92832390/165194428-fda73f03-dbef-4b2d-b63e-f0d2b2148b61.png)
Creación de modelo, con el correspondiente controlador y los recursos necesarios. -mcr es la instruccion crea el modelo con su controlador y los recursos
********
![image](https://user-images.githubusercontent.com/92832390/165195794-ed89adb7-82a7-440c-abbc-c4bb69e770d0.png)
Al crearse la migracion correspondiente a la tabla del modelo, se puede modificar la migracion y usar artisan migrate de nuevo para actualizar la tabla en la base de datos
********
![image](https://user-images.githubusercontent.com/92832390/165196703-adf29ca8-5ffc-4748-b757-48fc7506b532.png)

Asignación de una ruta dentro de una vista Blade

![image](https://user-images.githubusercontent.com/92832390/165196828-fbeb711b-5c49-4ace-9fbc-303226372e89.png)
Creación de la ruta en el archivo web.php ubicado en la carpeta routes.
Con estos pasos se crea una ruta para el modelo, se puede ver la asignacion en un elemento de una vista y la creacion de la ruta en el archivo correspondiente
********
![image](https://user-images.githubusercontent.com/92832390/165199643-06833c5b-84d8-4544-97fe-c61738c33e2e.png)

 Posterior a la ruta se crea la vista en la carpeta resources/views  
 ********
 ![image](https://user-images.githubusercontent.com/92832390/165202812-3d029bff-a349-43e9-be11-7680450179f4.png)
 
Se crea el metodo en el controlador correspondiente al modelo

********
![image](https://user-images.githubusercontent.com/92832390/165202983-9bd120ee-cf06-460a-b4d1-d8e73b8c9bee.png)

Ejemplo de la vista que nos aparece despues de la creacion del metodo en el controlador
********
![image](https://user-images.githubusercontent.com/92832390/165412156-9e6b47a8-9e6d-4321-b84f-407e5d9167d5.png)

Metodos crear del controlador

![image](https://user-images.githubusercontent.com/92832390/165412235-51ac0f0f-5e71-45ed-a879-6fecb6e9eafa.png)

Vista del formulario crear
*********
![image](https://user-images.githubusercontent.com/92832390/165422838-04861380-49cf-43d1-982e-8aa4502af4e4.png)

Se crea una vista para definir el layout y el elemento form, donde se llama el metodo store del controlador, y se incluye la vista formulario

![image](https://user-images.githubusercontent.com/92832390/165422905-f224a5b8-3eab-49d3-9bd1-6b84d08ba572.png)

Metodo Listar para las tablas

**************
![image](https://user-images.githubusercontent.com/92832390/166605023-1bfdebb1-4ea6-4889-9fe1-f865086956af.png)

Metodo para crear nuevo registro

![image](https://user-images.githubusercontent.com/92832390/166605073-43d6cdab-dd09-4b9f-b58c-b060942678a9.png)

Formulario para creacion. El formulario se hace en una vista aparte y se incluye en la vista llamada por el controlador 

**************
![image](https://user-images.githubusercontent.com/92832390/166605154-19117ce1-c3e7-4044-ab62-092a7bf091bb.png)

Metodo para ver y editar registros

![image](https://user-images.githubusercontent.com/92832390/166605190-99df4c88-5b4d-4a57-805a-7f43cc4c58be.png)

Vista del formulario de actualizacion

![image](https://user-images.githubusercontent.com/92832390/166605237-c1204e23-0917-4570-abc2-05226a88a0b9.png)

Metodo para eliminar registros
