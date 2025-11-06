# Plantillas de AGENTS para agentes autónomos

Este repositorio recopila plantillas de archivos `AGENTS.md` que sirven como punto de partida para configurar agentes en distintos lenguajes y contextos. Cada carpeta contiene una guía con convenciones de estilo, estructura recomendada y comandos útiles para el stack tecnológico correspondiente.

## Estructura del repositorio

- `C#/` – Recomendaciones para proyectos .NET, incluyendo estructura por capas, configuración de `Nullable`, uso de inyección de dependencias y comandos habituales (`dotnet restore`, `dotnet build`, `dotnet test`).
- `Java/` – Lineamientos para aplicaciones Java con Gradle o Maven, uso de Java 17+, patrones de capas y recordatorios sobre documentación con Javadoc.
- `JavaScript/` – Guía orientada a proyectos Node.js/TypeScript con pautas de estilo, scripts sugeridos y prácticas para manejar dependencias, linters y formateadores como ESLint y Prettier.
- `Python/` – Sugerencias para proyectos Python con virtualenv o `poetry`, estructura modular, tipado opcional y herramientas habituales como `pytest` y linters (`ruff`, `flake8`).
- `desarollo_paginas_web/` – Plantilla enfocada en proyectos web estáticos o SPA con recomendaciones de estructura, estándares HTML/CSS/JS y flujos de trabajo con herramientas de build.

Cada subdirectorio puede incluir subcarpetas adicionales; las instrucciones de su `AGENTS.md` aplican recursivamente a todo su contenido.

## Cómo utilizar estas plantillas

1. Copia el archivo `AGENTS.md` del lenguaje o contexto que necesites al directorio raíz de tu proyecto.
2. Adapta la información (versiones, comandos, herramientas) a las necesidades específicas de tu equipo.
3. Añade instrucciones adicionales para módulos o carpetas concretas creando nuevos `AGENTS.md` anidados.
4. Mantén actualizadas las guías conforme evolucione tu stack y comparte estos cambios con tu equipo.

## Recomendaciones generales

- Conserva los `AGENTS.md` junto al código que describen para evitar que las convenciones queden desactualizadas.
- Documenta cómo ejecutar pruebas, linters y pipelines para reducir la fricción en nuevos colaboradores o agentes automáticos.
- Revisa periódicamente que las instrucciones sigan alineadas con las herramientas y versiones usadas en producción.

Con estas plantillas podrás estandarizar rápidamente la configuración de agentes autónomos en diferentes lenguajes y mantener la consistencia en tus repositorios.