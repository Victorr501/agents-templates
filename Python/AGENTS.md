# Guía rápida Python

## Estructura sugerida
- `src/` o `app/`: código principal dividido en módulos (`domain`, `services`, `adapters`).
- `tests/`: organiza por la misma estructura que `src/`.
- `pyproject.toml` o `requirements.txt`: dependencias y herramientas.

## Buenas prácticas básicas
- Usa Python 3.12 (ajusta si el proyecto fija otra versión).
- Activa un entorno virtual y registra dependencias con `pip-tools` o `poetry`.
- Mantén funciones cortas, con tipado opcional (`from __future__ import annotations`).
- Evita lógica en `__init__.py`; usa módulos explícitos.
- Maneja la configuración mediante variables de entorno.

## Conveción de nombres y documentación
- Variables y funciones en snake_cases
- Clases en PascalCase
- Constantes en ALL_UPPER_CASE
- Usa docstring para la documentacion y hazme una documentacion de todos los metodos

## Comandos útiles
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
pytest
```

Antes de abrir una PR ejecuta `pytest` y un linter (`ruff` o `flake8`) si está disponible.