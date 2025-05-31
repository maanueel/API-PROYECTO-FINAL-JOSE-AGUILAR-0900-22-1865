1. Importar la Colección JSON en Postman
Abrir Postman: Inicia la aplicación Postman en tu computadora.

Importar la Colección:

En la barra lateral izquierda, haz clic en el botón Import.
Selecciona la pestaña File.
Haz clic en Choose Files y navega hasta el archivo PostmanCollection.json que se encuentra en la raíz del proyecto.
Haz clic en Open para seleccionar el archivo.
Luego, haz clic en Import para cargar la colección.
Verificar la Colección: Asegúrate de que la colección "Credit Card Management API" aparece en la barra lateral de Postman.

2. Configurar el Entorno de Desarrollo
2.1. Requisitos Previos
Asegúrate de tener instalado .NET 6 SDK o superior.
Instala Visual Studio 2022 o cualquier IDE compatible con .NET.

3. Ejecutar la aplicación
4. Verificar la URL de la API: Por defecto, la API estará disponible en:

http://localhost:5156 (HTTP)
https://localhost:7244 (HTTPS)
Probar la API con Postman
Abrir Postman: Si no está abierto, inicia Postman.

Seleccionar la Colección: En la barra lateral, selecciona la colección "Credit Card Management API".

Ejecutar Peticiones:

Crear Cliente: Haz clic en la petición "Crear Cliente" y luego en Send. Asegúrate de que el cuerpo de la solicitud contenga un JSON válido.
Obtener Cliente: Cambia el ID en la URL de la petición "Obtener Cliente" y haz clic en Send.
Actualizar Cliente: Modifica el JSON en la petición "Actualizar Cliente" y haz clic en Send.
Eliminar Cliente: Cambia el ID en la URL de la petición "Eliminar Cliente" y haz clic en Send.
Listar Clientes: Haz clic en la petición "Listar Clientes" y luego en Send.
