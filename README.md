# 🧩 Proyecto Final – Infraestructura Computacional

## Virtualización con Docker + Volúmenes Persistentes

Este proyecto implementa una solución de virtualización basada en contenedores, utilizando Docker para desplegar servicios esenciales de manera modular, eficiente y aislada. La solución se centra en la creación de imágenes personalizadas y el despliegue de contenedores con almacenamiento persistente, garantizando estabilidad y continuidad operativa para cada servicio.

## 📌 Contexto del Proyecto

Una organización busca centralizar sus servicios tecnológicos en un nuevo servidor con mayor capacidad. Para ello, se requiere migrar tres servicios fundamentales (Apache, MySQL y Nginx) hacia una arquitectura basada en contenedores, con almacenamiento seguro y persistente.

## 🎯 Objetivo General

Implementar una plataforma de virtualización por contenedores que permita:

- Ejecutar servicios web y de base de datos en contenedores independientes.
- Crear imágenes personalizadas con Docker.
- Mantener datos persistentes mediante volúmenes dedicados para cada servicio.
- Validar la persistencia y funcionamiento correcto de toda la infraestructura.

## ⚙️ Requerimientos del Proyecto

### 💠 Virtualización y Contenedores

Se deben crear 3 contenedores, uno para cada servicio:

- Apache
- MySQL
- Nginx

Cada contenedor se construye a partir de una imagen personalizada, generada mediante:

- `Dockerfile` (para Docker)

Además, debe demostrarse la ejecución en:

- Docker

### 💠 Pruebas de Funcionamiento

El proyecto debe demostrar:

- Acceso correcto a páginas web servidas por Apache y Nginx.
- Acceso, creación y consulta de bases de datos en MySQL.
- Funcionamiento correcto de contenedores en ambos sistemas de virtualización.

### 💠 Pruebas de Persistencia

Se debe comprobar que los datos persisten incluso después de:

- Detener contenedores
- Eliminarlos
- Volver a crearlos

## 👤 Autores
-Sara Otero Echeverry
-Mariajosé Valencia Diaz 
