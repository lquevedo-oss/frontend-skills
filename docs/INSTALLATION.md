# Instalación

## Con el instalador de Codex

Invoca `skill-installer` y proporciona la URL de este repositorio y las tres rutas `skills/frontend-studio`, `skills/frontend-directions` y `skills/godly-inspiration`.

Si ya tienes una skill con el mismo nombre, revisa las diferencias antes de sustituirla. No instales varias copias esperando que sus instrucciones se fusionen.

## Instalación manual

1. Clona o descarga este repositorio.
2. Copia las carpetas que necesites desde `skills/` a `.agents/skills/` dentro de tu proyecto.
3. Para usarlas en varios proyectos, puedes colocarlas en `~/.agents/skills/`.
4. Comprueba que cada carpeta contenga su `SKILL.md`.
5. Si no aparecen en Codex, reinicia la aplicación o sesión.

Ejemplo de estructura dentro de un proyecto:

```text
.agents/
  skills/
    frontend-studio/SKILL.md
    frontend-directions/SKILL.md
    godly-inspiration/SKILL.md
```

Estas ubicaciones siguen la [documentación oficial de skills](https://learn.chatgpt.com/docs/build-skills), consultada el 5 de octubre de 2026. Versiones o instalaciones anteriores pueden usar ubicaciones diferentes; respeta la configuración de tu entorno.

## Requisitos

- Un entorno Codex con soporte de skills.
- Acceso al código del proyecto para implementar cambios.
- Navegador o herramienta equivalente para revisar interfaces renderizadas.
- Acceso a la web para investigar referencias con Godly Inspiration.

No se necesitan claves de API para leer estas instrucciones. Las capacidades del agente dependen del entorno donde las uses.

## Complementos

Los complementos mencionados por Studio se instalan por separado; revisa [las fuentes](../CREDITS.md). No son dependencias descargadas automáticamente.

Si un complemento no está disponible, la colección puede orientar el trabajo, pero no incluye su contenido especializado. Indica al agente que continúe con lo disponible y documente esa limitación.

## Actualizar

Descarga la nueva versión o ejecuta `git pull` en tu clon. Compara los `SKILL.md` con las copias instaladas y conserva tus cambios locales antes de reemplazarlas. Actualizar el clon no modifica automáticamente las carpetas que copiaste a otro proyecto.

Este repositorio publica carpetas de skills; no está registrado como plugin en un marketplace.
