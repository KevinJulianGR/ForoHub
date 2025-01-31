# Challenge ONE - API REST Foro Alura

## Descripción del Proyecto
Una implementación de API REST desarrollada con **Java** y **Spring Boot** para gestionar un sistema de foro de discusión. Este proyecto forma parte del cuarto desafío del programa **Oracle Next Education (ONE)**, una iniciativa de **Oracle** y **Alura LATAM**.

## Características Generales
Este sistema permite gestionar tópicos, respuestas e interacciones en una plataforma colaborativa diseñada para estudiantes de diversos cursos. Su objetivo principal es proporcionar una infraestructura backend eficiente y robusta, siguiendo las mejores prácticas de desarrollo.

### Principales Funcionalidades
- **Creación de tópicos:** Permite a los usuarios crear nuevos temas de discusión.
- **Listado de tópicos:** Proporciona un listado completo de los tópicos existentes.
- **Detalles de tópicos:** Permite consultar información detallada de un tópico específico.
- **Actualización de tópicos:** Facilita la modificación del contenido de los tópicos existentes.
- **Eliminación de tópicos:** Posibilita la eliminación de tópicos del sistema.
- **Arquitectura REST:** Implementación basada en principios y mejores prácticas de diseño REST.
- **Validación de negocio:** Garantiza validaciones adecuadas en todas las operaciones.
- **Persistencia de datos:** Integra una base de datos **MySQL** para almacenar la información de manera segura y eficiente.

## Contexto del Proyecto
El **Foro Alura** es una plataforma que permite a estudiantes, profesores y moderadores interactuar mediante la publicación y resolución de preguntas relacionadas con diversos cursos. Este proyecto desarrolla la funcionalidad backend necesaria para gestionar estas interacciones.

## Stack Tecnológico
- **Java 17**: Lenguaje principal de desarrollo.
- **Spring Boot 3.1.0**: Framework utilizado para la creación de la API.
- **MySQL**: Base de datos relacional para la persistencia de datos.
- **IntelliJ IDEA**: IDE empleado para el desarrollo del proyecto.
- **Insomnia**: Herramienta utilizada para realizar pruebas de la API.
- **Trello**: Plataforma para la gestión y seguimiento de tareas del proyecto.

## Instalación y Ejecución
1. Clona este repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```
2. Importa el proyecto en tu IDE (recomendado: IntelliJ IDEA).
3. Configura la base de datos MySQL en el archivo `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/foro_alura
   spring.datasource.username=tu_usuario
   spring.datasource.password=tu_contraseña
   ```
4. Ejecuta la aplicación desde la clase principal.
5. Prueba las funcionalidades utilizando Insomnia u otra herramienta de tu preferencia.

## Arquitectura y Diseño
La API está diseñada siguiendo los principios de las arquitecturas REST, asegurando una estructura robusta, modular y escalable. Las validaciones se aplican en cada operación para garantizar la integridad de los datos y se utiliza una base de datos relacional para almacenar la información de manera estructurada.

## Contribuciones
Las contribuciones son bienvenidas. Si deseas colaborar, sigue estos pasos:
1. Haz un fork del repositorio.
2. Crea una rama para tu función o corrección:
   ```bash
   git checkout -b feature/nueva-funcionalidad
   ```
3. Realiza tus cambios y haz un commit:
   ```bash
   git commit -m "Agrega nueva funcionalidad"
   ```
4. Sube tus cambios a tu repositorio remoto:
   ```bash
   git push origin feature/nueva-funcionalidad
   ```
5. Abre un Pull Request en este repositorio.

## Licencia
Este proyecto está licenciado bajo la [MIT License](LICENSE).

---
**Nota:** Este proyecto es parte del programa educativo y no está destinado a producción.


