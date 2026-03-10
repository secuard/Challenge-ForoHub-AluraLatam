# ForoHub System

ForoHub es una plataforma basada en Spring Boot diseñada para crear, gestionar y participar en foros educativos. Este proyecto implementa un sistema robusto y seguro para usuarios, temas, cursos y respuestas.

---

## *Tabla de Contenidos*

1. [Características](#características)
2. [Arquitectura del Sistema](#arquitectura-del-sistema)


## *Características*
- **Gestión de Usuarios**: Autenticación y autorización con JWT.
- **Gestión de Foros**: Creación y visualización de temas y respuestas.
- **Gestión de Cursos**: Asociación de cursos con temas y categorías.
- **Documentación de la API**: Generada con Swagger.
- **Seguridad**: Implementación de roles y permisos con Spring Security.

---

## *Arquitectura del Sistema*

El proyecto está diseñado con una arquitectura por capas:
- **Capa API**: Contiene los controladores REST y configuraciones de seguridad.
- **Capa de Dominio**: Define las entidades, repositorios y DTOs.
- **Capa de Infraestructura**: Incluye configuración de base de datos, manejo de errores y documentación de API.

