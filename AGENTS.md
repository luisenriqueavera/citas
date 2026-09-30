# Agente orquestador del workspace citas

Este workspace contiene dos repositorios independientes: `citas-api` y `citas-web`.

## Reglas

- Leer `PRD.md`, `RESTRICCIONES_TECNICAS.md` y las HU antes de modificar código.
- Mantener la lógica de negocio en `citas-api` y la UI en `citas-web`.
- El frontend consume directamente la API REST; no crear BFF ni Express.
- Todo cambio de contrato REST debe verificarse en ambos repositorios.
- Trabajar en `develop`; `main` representa puntos estables.
- No incluir secretos, tokens, contraseñas ni datos reales de FCV.
- No implementar S4–S6 mientras el gate LOOP_00 de S1–S3 no esté en verde.

## Wiki

La wiki global está en `citas-api/docs/wiki/llm-wiki/`. Las fuentes raw son inmutables; las páginas wiki registran hechos verificados, decisiones y riesgos.
