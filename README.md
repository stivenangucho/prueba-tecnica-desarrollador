# Prueba Técnica - CRUD de Empleados en PHP + MySQL

Este proyecto fue desarrollado como prueba técnica para demostrar habilidades en desarrollo web con PHP, programación orientada a objetos, uso de base de datos relacional (MySQL), validación de formularios y diseño responsivo.

---

## Tecnologías utilizadas

- **PHP** 
- **MySQL**
- **HTML5, CSS3, JavaScript**
- **Apache (XAMPP) entorno de desarrollo local**

---

El sistema permite gestionar empleados con sus datos básicos, área de trabajo y uno o varios roles asignados. Incluye operaciones CRUD completas:

- Crear nuevo empleado
- Editar información
- Eliminar registro
- Listar empleados existentes

También implementa validaciones tanto del lado del cliente (JavaScript) como del servidor (PHP) para garantizar el ingreso correcto de los datos.

---

## Repositorio público en GitHub

https://github.com/stivenangucho/prueba-tecnica-desarrollador

---

## Requisitos para ejecutar

1. Tener XAMPP o similar instalado
2. Clonar o copiar el proyecto en `C:/xampp/htdocs/prueba-nexura`
3. Iniciar Apache y MySQL desde XAMPP
4. Crear una base de datos llamada `base_datos_nexura`
5. Importar el archivo SQL ubicado en:  
   `db/base_datos_nexura`
6. Abrir en el navegador:  
   `http://localhost/prueba-nexura`

---

## Estructura del proyecto
prueba-nexura/

├── assets/

      │ └── style.css

├── config/

      │ └── conexion.php

      │ └── config.php

├── controllers/

      │└── actualizar.php

      │└── eliminar.php

      │└── guardar.php

├── db/

      │└── base_datos_nexura.sql

├── models/

      │└── empleado.php

├── views/

      |── empleados/

            │└── crear.php

            │└── editar.php

|── index.php

|── README.md

---

## Autor

Stiven Angucho Valencia

anguchostiven@gmail.com

Julio 2025

---
