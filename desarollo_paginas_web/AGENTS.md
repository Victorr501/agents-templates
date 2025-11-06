# Guía rápida Desarrollo Web (HTML, CSS y JavaScript)

## Estructura sugerida
- `public/` o `static/`: archivos HTML base.
- `assets/css/`: hojas de estilo organizadas por componentes o páginas.
- `assets/js/`: scripts modulares.
- `assets/img/`: imágenes y recursos.

## Buenas prácticas básicas
- Usa HTML semántico (`header`, `main`, `footer`).
- Mantén CSS dividido en archivos pequeños y reutiliza variables (`:root { --color-primario: ... }`).
- Coloca el JavaScript al final del `<body>` o usa `defer`.
- Añade atributos `alt` descriptivos a las imágenes y textos adecuados para accesibilidad.
- Evita estilos en línea y mezcla mínima de lógica en el HTML.

## Conveción de nombres y documentación
- Variables y funciones en camelCase
- Clases en PascalCase
- Constantes en ALL_UPPER_CASE
- Usa JSDoc para la documentacion y hazme una documentacion de todos los metodos

## Flujo de trabajo recomendado
```bash
npm install # si hay herramientas de build
npm run dev # servidor local
npm run build # versión optimizada
```

Antes de publicar revisa accesibilidad básica (tabulación, contraste) y prueba en al menos un navegador móvil y uno de escritorio.