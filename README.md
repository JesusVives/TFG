# TFG
# TIENDA ONLINE

## Descripción

Tienda Online es una aplicación web desarrollada como Trabajo de Fin de Grado del ciclo formativo de Sistemas Microinformáticos y Redes.

La aplicación permite gestionar productos, usuarios, carritos de compra y pedidos mediante una plataforma web accesible desde cualquier navegador.

El proyecto ha sido desarrollado completamente mediante programación web utilizando HTML, CSS, JavaScript, PHP y MySQL, sin utilizar gestores de contenido como WordPress.

---

## Funcionalidades principales

### Usuarios

- Registro de usuarios.
- Inicio de sesión.
- Cierre de sesión.
- Gestión de perfil.
- Consulta de pedidos.

### Productos

- Visualización de catálogo.
- Búsqueda de productos.
- Filtrado por categorías.
- Visualización de detalles.

### Carrito

- Añadir productos.
- Eliminar productos.
- Modificar cantidades.
- Calcular importe total.

### Administración

- Alta de productos.
- Modificación de productos.
- Eliminación de productos.
- Gestión de categorías.
- Gestión de pedidos.

---

## Tecnologías utilizadas

### Frontend

- HTML5
- CSS3
- JavaScript

### Backend

- PHP 8

### Base de datos

- MySQL

### Servidor web

- Apache

### Entorno de desarrollo

- Visual Studio Code
- XAMPP

---

## Requisitos mínimos

- Sistema operativo Windows, Linux o macOS.
- XAMPP instalado.
- PHP 8 o superior.
- MySQL 8 o superior.
- Navegador web moderno.

---

## Instalación

### Paso 1

Clonar el repositorio:

git clone https://github.com/usuario/tienda-online.git

### Paso 2

Copiar el proyecto dentro de:

C:\xampp\htdocs\

### Paso 3

Iniciar:

- Apache
- MySQL

desde el panel de control de XAMPP.

### Paso 4

Crear una base de datos llamada:

tienda_online

### Paso 5

Importar el archivo:

sql/tienda_online.sql

mediante phpMyAdmin.

### Paso 6

Acceder desde el navegador:

http://localhost/tienda-online

---

## Estructura del proyecto

tienda-online/

├── css/

├── js/

├── img/

├── php/

├── sql/

├── index.php

├── login.php

├── registro.php

├── catalogo.php

├── carrito.php

├── contacto.php

└── README.md

---

## Base de datos

La base de datos está formada por las siguientes tablas:

- usuarios
- productos
- categorias
- carritos
- carrito_productos
- pedidos
- pedido_productos
- imagenes_producto
- contactos

---

## Seguridad

El sistema incorpora:

- Validación de formularios.
- Gestión de sesiones.
- Restricción de acceso al panel administrador.
- Protección básica de datos.

---

## Autor

Nombre: Jseús Vives Hernández

Centro educativo: The Power

Ciclo Formativo:
Sistemas Microinformáticos y Redes

Curso:
2025-2026

Proyecto:
Trabajo de Fin de Grado

---

## Licencia

Proyecto desarrollado exclusivamente con fines educativos.
