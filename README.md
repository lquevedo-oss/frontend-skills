# Frontend Skills

**Un flujo de diseño frontend para Codex: entender, explorar, construir y revisar.**

Colección personal mantenida por [Luka Quevedo](https://github.com/lquevedo-oss), desarrollada e iterada con asistencia de Codex. Reúne instrucciones reutilizables para trabajar el diseño visual, la navegación y la revisión de interfaces sin perder de vista el producto y su sistema de diseño.

Las skills son instrucciones para un agente: no son una biblioteca de componentes ni garantizan un resultado visual por sí solas. El brief, los recursos disponibles y la revisión humana siguen siendo importantes.

## Skills incluidas

| Skill | Qué aporta | Cuándo usarla |
| --- | --- | --- |
| [Frontend Studio](skills/frontend-studio/SKILL.md) | Coordina análisis, diseño, implementación y verificación visual. | Crear o rediseñar una página, componente o aplicación. |
| [Frontend Directions](skills/frontend-directions/SKILL.md) | Explora dos o tres direcciones con diferencias reales de composición y jerarquía. | Comparar alternativas antes de decidir. |
| [Godly Inspiration](skills/godly-inspiration/SKILL.md) | Investiga referencias actuales y traduce decisiones útiles al contexto del proyecto. | Buscar una dirección visual cuando el brief está abierto. |

## Empezar

Pídele a Codex:

```text
Usa $skill-installer para instalar desde
https://github.com/lquevedo-oss/frontend-skills
las skills de estas carpetas:
- skills/frontend-studio
- skills/frontend-directions
- skills/godly-inspiration
```

Luego, en tu proyecto:

```text
Usa frontend-studio para mejorar esta interfaz.
Conserva las funciones existentes y la identidad de marca.
Prioriza claridad, navegación y legibilidad.
Implementa los cambios y revisa el resultado en escritorio y móvil.
```

Consulta [la guía de instalación](docs/INSTALLATION.md) para la alternativa manual y cómo actualizar.

## Cómo se combinan

1. **Studio** revisa el brief, el código y los recursos existentes.
2. **Directions** entra si hace falta comparar alternativas.
3. **Godly Inspiration** aporta referencias cuando la dirección está abierta.
4. El agente implementa con el stack existente y revisa el resultado renderizado.

No todas las tareas requieren todas las skills. Un cambio de texto o espaciado no necesita investigación visual ni tres propuestas.

## Complementos externos

Studio menciona otras skills especializadas: `frontend-design`, `ui-ux-pro-max`, `transitions-dev`, `animate` y `mobile-native`. **No vienen incluidas en este repositorio.** Instálalas por separado si quieres reproducir el conjunto completo.

Si falta alguna, pide a Codex continuar con las instrucciones disponibles e indicar qué parte no pudo aplicar. Nunca debe afirmar que cargó una skill que no tiene.

Fuentes y autoría: [CREDITS.md](CREDITS.md).

## Documentación

- [Instalación y actualización](docs/INSTALLATION.md)
- [Ejemplos de prompts](docs/EXAMPLES.md)
- [Guía de revisión](docs/REVIEW.md)
- [Créditos y procedencia](CREDITS.md)
- [Cómo contribuir](CONTRIBUTING.md)
- [Historial de cambios](CHANGELOG.md)

## Estado

Primera edición de una colección en evolución. Las tres skills provienen de un flujo personal de trabajo; esta publicación inicial conserva sus instrucciones. La validación de estructura y contenido no sustituye una evaluación comparativa de resultados.

Los ejemplos son genéricos. No se incluyen código, capturas, datos ni recursos de proyectos privados.

## Licencia

El contenido incluido se distribuye bajo [MIT](LICENSE). Las herramientas, sitios y skills externas conservan sus propias licencias. Este proyecto no está afiliado a OpenAI, Anthropic, Godly ni a los autores citados.
