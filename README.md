<div align="center">

# Enrique Corpus
### Backend Developer · Java · Spring Boot · SQL · NoSQL

[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/3105261024)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/enrique-corpus-9a1b9a329/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:enrique.corpus.5004@hotmail.com)

</div>

---

## Sobre mí

Desarrollador backend especializado en **Java y Spring Boot**, con enfoque en el diseño de APIs REST, arquitecturas en capas y modelado de bases de datos relacionales y NoSQL. Construyo sistemas que resuelven problemas de negocio reales: control de inventario, auditoría de operaciones, gestión de transacciones y automatización de flujos de datos.

Mi stack principal es **Java · Spring Boot · MySQL · MongoDB**, complementado con conocimiento en seguridad (JWT, Spring Security), documentación de APIs (Swagger/OpenAPI) y patrones de diseño aplicados (DAO, Singleton, Facade, Prototype).

---

## Stack Tecnológico

### Backend
<div align="center">

[![Skills](https://skillicons.dev/icons?i=java,spring,py)](https://skillicons.dev)

</div>

### Bases de datos
<div align="center">

[![Skills](https://skillicons.dev/icons?i=mysql,mongodb)](https://skillicons.dev)

</div>

### Herramientas
<div align="center">

[![Skills](https://skillicons.dev/icons?i=git,github,postman,vscode)](https://skillicons.dev)

</div>

### Frontend (complementario)
<div align="center">

[![Skills](https://skillicons.dev/icons?i=js,html,css)](https://skillicons.dev)

</div>

---

## Proyectos

### LogiTrack — Sistema de Gestión y Auditoría de Bodegas
> `Spring Boot 3` · `Java 17` · `Spring Security` · `JWT` · `MySQL` · `Swagger/OpenAPI` · `JPA`

Sistema backend para la administración de bodegas distribuidas en múltiples ciudades. Gestiona productos, controla movimientos de inventario (entradas, salidas, traslados, ajustes) y mantiene una auditoría automática de todos los cambios por usuario.

**Aspectos técnicos destacados:**
- API REST con autenticación JWT y control de acceso por roles (ADMIN, SUPERVISOR, OPERARIO)
- Arquitectura en 3 capas: Controller → Service → Repository con DTOs y Mappers
- Auditoría automática con listeners que registran JSON de cambios por operación
- Documentación completa con SpringDoc OpenAPI (Swagger UI)
- Validaciones con Bean Validation y manejo centralizado de errores con `@ControllerAdvice`
- 14 entidades relacionadas con constraints e integridad referencial en MySQL

[![Ver repositorio](https://img.shields.io/badge/Ver_repositorio-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kikecorpus)

---

### TecnoStore — Sistema de Gestión para Tienda de Celulares
> `Java 25` · `JDBC` · `MySQL` · `Maven` · `Patrones de Diseño`

Aplicación Java que cubre el ciclo completo de ventas de una tienda: inventario, clientes, ventas con múltiples ítems, facturación, reportes y análisis estadísticos. Conexión directa a MySQL mediante JDBC.

**Aspectos técnicos destacados:**
- Patrones de diseño aplicados: **Singleton** (conexión BD con double-checked locking), **Prototype** (clonación de entidades para edición con comparativa), **Facade** (flujo de venta completa), **DAO** (acceso a datos desacoplado)
- Stream API y Optional para operaciones sobre colecciones sin bucles explícitos
- PreparedStatement con `RETURN_GENERATED_KEYS` para inserciones seguras
- Validaciones robustas: formatos de correo, integridad referencial, rangos de menú y fechas
- Exportación de reportes a `.txt` con apertura automática del archivo

[![Ver repositorio](https://img.shields.io/badge/Ver_repositorio-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kikecorpus)

---

### Pizzería Don Piccolo — Modelado de Base de Datos Relacional
> `MySQL 8` · `Triggers` · `Stored Procedures` · `Functions` · `Views`

Base de datos relacional que automatiza las operaciones de una cadena de pizzerías: registro de pedidos, cálculo de precios y costos, seguimiento de domicilios y control financiero. Toda la lógica de negocio está encapsulada en la base de datos.

**Aspectos técnicos destacados:**
- Pipeline de automatización con triggers encadenados: `BEFORE INSERT` → `AFTER INSERT` → actualización en cascada de costos y totales
- 6 funciones almacenadas para cálculo de costos por porción, precio con IVA y totales de pedido
- 15+ procedimientos almacenados que encapsulan flujos de inserción complejos
- Solución documentada al Error 1442 (tabla mutante) mediante procedimientos en lugar de triggers anidados
- 15 entidades con herencia modelada en MySQL (Persona → Cliente/Vendedor/Repartidor)

[![Ver repositorio](https://img.shields.io/badge/Ver_repositorio-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kikecorpus)

---

### Campus Music — Sistema de Gestión NoSQL
> `MongoDB` · `Aggregation Pipeline` · `Transacciones ACID` · `JSON Schema` · `Roles`

Base de datos NoSQL para la gestión de escuelas de música distribuidas en Colombia: estudiantes, profesores, cursos, inscripciones y préstamos de instrumentos.

**Aspectos técnicos destacados:**
- Modelo de datos orientado a documentos con validaciones JSON Schema por colección
- Aggregation Pipeline para reportes analíticos complejos
- Transacciones ACID multi-documento para flujos de inscripción
- Control de acceso granular con roles de MongoDB

[![Ver repositorio](https://img.shields.io/badge/Ver_repositorio-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kikecorpus)

---

### Otros proyectos

| Proyecto | Tecnología | Descripción |
|---|---|---|
| Simulador de Gastos Diario | Python | Registro y análisis de gastos personales por consola |
| Plataforma LMS | JS Vanilla · HTML · CSS | Plataforma de aprendizaje con interfaz web completa |
| Juego de Poker | JavaScript | Implementación de reglas y lógica del juego |
| Buscador de Pokémon | JavaScript · REST API | Consumo de PokéAPI con filtros dinámicos |

---

## Estadísticas de GitHub

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=kikecorpus&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=kikecorpus&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=kikecorpus&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/3105261024)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/enrique-corpus-9a1b9a329/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:enrique.corpus.5004@hotmail.com)

</div>
