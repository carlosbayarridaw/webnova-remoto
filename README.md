# Práctica 5 — Entregable

**Carlos · Despliegue de Aplicaciones Web**

## 1. Error al hacer `git push`

![Captura 1 - Git muestra rejected](capturas/01_error_rejected.png)

## 2. Conflicto antes de resolverlo

![Captura 2 - Marcas del conflicto](capturas/02_conflicto_sin_resolver.png)

## 3. Resultado final en GitHub

![Captura 3 - equipo.md con los tres miembros](capturas/03_github_final.png)

## 4. Pregunta de reflexión

Git rechazó el push porque en github ya había cambios que yo todavía no tenía en local, me pasó algo parecido en la práctica anterior con los HTML, pero allí el conflicto fue entre dos ramas y esta vez entre mi repositorio local y github.

Para solucionarlo usé git pull --rebase, que primero trae los cambios de github y después aplica los míos. Como los dos habíamos modificado el mismo archivo, tuve que juntar los cambios para poder subirlo todo sin crear un commit extra con merge, dejando el historial más ordenado y en línea recta.
