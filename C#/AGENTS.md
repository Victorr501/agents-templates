# Guía rápida C#

## Estructura sugerida
- `Domain/`: modelos y reglas de negocio.
- `Application/`: casos de uso y validaciones.
- `Infrastructure/`: acceso a datos y servicios externos.
- `Presentation/` o `Api/`: controladores o endpoints.
- `tests/`: misma estructura que la aplicación.

## Buenas prácticas básicas
- Trabaja con `net8.0` (o la versión fijada en `global.json`).
- Habilita `Nullable` y usa inyección de dependencias.
- Nombra tipos en `PascalCase` y variables en `camelCase`.
- Prefiere clases pequeñas y métodos cortos; evita lógica duplicada.
- Documenta decisiones especiales en el README del módulo.

## Conveción de nombres y documentación
- Variables y funciones en camelCase
- Clases en PascalCase
- Constantes en ALL_UPPER_CASE
- Usa XML Docs para la documentacion y hazme una documentacion de todos los metodos

## Comandos útiles
```bash
dotnet restore
dotnet build
dotnet test
```

Antes de abrir una PR asegúrate de que `dotnet test` pase y de que el código esté formateado (`dotnet format`).