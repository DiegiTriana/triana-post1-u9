# triana-post1-u9

Microservicio de productos para la actividad U9 Post-Contenido 1, con pruebas unitarias de la capa de servicio usando JUnit 5 y Mockito.

## Tecnologias

- Java 21
- Spring Boot 3.3.12
- Spring Web + Spring Data JPA + H2
- JUnit 5 + Mockito

## Ejecutar

```bash
mvn clean test
```

## Estructura principal

- `domain/Producto`: entidad JPA.
- `repository/ProductoRepository`: acceso a datos.
- `service/ProductoService` y `ProductoServiceImpl`: reglas de negocio y validaciones.
- `controller/ProductoController`: endpoints REST.
- `src/test/.../ProductoServiceImplTest`: suite unitaria completa.

## Evidencia de pruebas en verde

![Test aprobado](docs/mvn-test-success.png)
