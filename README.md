# Prueba tecnica Afore Coppel
Crea un repositorio en GitHub para el proyecto. 
El proyecto consiste en la elaboración de una servicio REST para el manejo de usuarios y productos con un frontend basico

> Procura realizar por lo menos un commit por feature.

## Feature 1 Backend setup:
Configura un ambiente basico para empezar a codificar, nosotros utlizamos tecnologias como SpringBoot (Java) o Codeigniter (PHP), pero puedes utilizar el framework con el que te sientas mas familiarizado.

Crea un endpoint con una respuesta de "Hola Mundo".

## Feature 2 Creación de base de datos en PostgreSQL
Crea un catalogo basico de sistema para manejar productos. Un producto debe contar por lo menos con la información basica como SKU, nombre, precio y marca o descripción.
De igual manera para los usuarios deben contar por lo menos con nombre, correo electronico y contraseña.

>
> En el sistema se deben tener al menos 2 tipos de usuarios: 
> - Administradores para crear, actualizar y eliminar productos y otros a usuarios
> - Usuarios anonimos que solo puedan obtener información de los productos pero no puedan realizar cambios.
>

Si un administrador realiza un cambio en un producto se debe de crear un log de dicho cambio.


## Feature 3 Interfaz de usuario
Crea una interfaz sencilla para la creación de los usuarios, login y menejo de los productos.

## Que esperamos
Vamos a evaluar tus decisiones en el diseño de la API y base de datos, toma tu tiempo para cada paso, no solo codificar. La prueba pueda sentirse un poco ambigua en ciertos puntos porque queremos que tomes decisiones de diseño.

### Puntos a evaluar
- Endpoints
- Integracion de la API en front
- Diseño de base de datos
- Funcionalidad de frontend (enfoque en funcionalidad no en diseño)
