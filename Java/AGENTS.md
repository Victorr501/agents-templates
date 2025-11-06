
# Guía rápida Java

## Estructura sugerida
- `src/main/java`: paquetes por capa (`domain`, `application`, `infrastructure`, `web`).
- `src/main/resources`: configuración y plantillas.
- `src/test/java`: repetir estructura de `main`.

## Buenas prácticas básicas
- Usa Gradle o Maven con Java 17 o superior.
- Mantén las clases con una responsabilidad clara.
- Expone interfaces en la capa de aplicación y aplica inyección de dependencias.
- Coloca configuraciones sensibles (URLs, claves) en variables de entorno.
- Añade comentarios breves solo cuando el código no sea evidente.

## Conveción de nombres y documentación
- Variables y funciones en camelCase
- Clases en PascalCase
- Constantes en ALL_UPPER_CASE
- Usa Javadoc para la documentacion y hazme una documentacion de todos los metodos


## Comandos útiles (Gradle)
```bash
./gradlew clean build
./gradlew test
```

Comprueba que las pruebas unitarias pasen y que el formato sea consistente (`./gradlew spotlessApply` si está disponible).