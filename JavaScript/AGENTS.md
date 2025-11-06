# Guía rápida JavaScript (Node.js / Frontend)

## Estructura sugerida
- `src/`: código fuente organizado por módulos o características.
- `public/` o `dist/`: archivos estáticos generados.
- `tests/` o `__tests__/`: casos de prueba.

## Buenas prácticas básicas
- Usa Node.js LTS y registra la versión en `.nvmrc` o `package.json` (`engines`).
- Agrupa lógica compartida en utilidades reutilizables.
- Evita acceder directamente a variables globales; usa configuraciones por entorno.
- Prefiere funciones puras y componentes pequeños.
- Asegura un linter (ESLint) y formateador (Prettier) en el proyecto.

## Conveción de nombres y documentación
- Variables y funciones en camelCase
- Clases en PascalCase
- Constantes en ALL_UPPER_CASE
- Usa JSDoc para la documentacion y hazme una documentacion de todos los metodos


## Comandos útiles (npm)
```bash
npm install
npm run lint
npm test
npm run build
```

Antes de subir cambios ejecuta `npm run lint` y `npm test`.