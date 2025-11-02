# Guía de contribución a ISA-Home

¡Gracias por colaborar! Esta guía resume cómo proponer cambios con el menor roce posible.

## Antes de empezar
- Lee el README y revisa issues abiertos.
- Abre un issue para cambios grandes (propuesta técnica).
- Para bugs usa la plantilla **Bug report**; para mejoras, **Feature request**.

## Flujo de trabajo
1. Haz fork y crea una rama: `feat/...`, `fix/...`, `docs/...`
2. Usa **Conventional Commits** (p. ej., `feat(robot): add obstacle avoidance tweak`)
3. Asegúrate de que tests/lint pasan localmente.
4. Abre un Pull Request usando la plantilla; enlaza el issue (Closes #NN).

## Estilo y calidad
- Cambios pequeños y enfocados.
- Documenta lo que cambias (README/docs).
- Incluye tests cuando aplique.

## Revisión y merge
- 1–2 aprobaciones de maintainers.
- CI en verde.
- Estrategia por defecto: **Squash & merge**.

## Conducta y licencias
- Respeta el **Código de Conducta**.
- Aceptas que tu contribución se integre bajo las licencias descritas en `LICENSE` y `Sprint 2/Propiedad Intelectual/Licencias v1.pdf`.
