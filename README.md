# DeliveryGo - Clase 2 - Versión corregida

## Configuración
- Java 21
- Maven
- Spring Boot 3.5.16
- Spring Data JPA
- H2

## IntelliJ
1. Abrir `pom.xml` como proyecto Maven.
2. Project SDK: Java 21.
3. Run > Edit Configurations > JRE: Java 21.
4. Ejecutar `DeliveryGoPersistenceApplication`.

## H2
Abrir: http://localhost:8080/h2-console

JDBC URL: `jdbc:h2:mem:deliverygo`
User: `sa`
Password: vacío

## Correcciones
- Java 21 fijado en Maven.
- JMX deshabilitado desde Spring.
- Open-In-View deshabilitado.
- Puerto 8080 fijado.
- URL de H2 unificada en 8080.

Nota: si IntelliJ agrega `-Dcom.sun.management.jmxremote`, deshabilitar JMX en la configuración de ejecución del IDE.
# aplicaciones-interactivas
