---
name: frontend-studio
description: Design or redesign frontend pages, components, and web apps in Codex. Use for visual UI work to combine design research, UI UX Pro Max, distinctive art direction, implementation, and visual verification.
---

# Frontend Studio

Use this as the coordinating workflow for visual frontend work. Follow the user's brief and the project's existing design system first. Preserve the framework, component library, content model, and brand assets already in use unless the task calls for changing them.

## Direction

1. Inspect the relevant code, assets, tokens, and screenshots. Identify the page's audience, primary job, and content hierarchy. If the brief is open-ended, choose and state a concrete visual direction.
2. For a new page, app, or substantial redesign, use the installed `ui-ux-pro-max` skill to generate candidate style, palette, typography, layout, and UX guidance. Check each result against the actual product; reject mismatches. Treat its database as a starting point, not a prescribed theme.
3. Use `frontend-design` for subject-specific visual identity, restraint, copy, and avoiding template-like defaults. When external references would materially help, use `godly-inspiration` to inspect current examples. Adapt principles; do not copy a site.
4. If the user requests alternatives or the brief genuinely needs visual exploration, use `frontend-directions`. Otherwise select a direction and build it without requiring a routine approval step.

## Build and review

- Implement the requested interface in the project's stack. Make content, states, and interactions functional. Reuse established components and tokens where appropriate.
- For common component transitions, use `transitions-dev`. For custom motion decisions use `animate`. Animate purposeful state changes and honor reduced-motion preferences.
- For touch-heavy or mobile-first web UI, use `mobile-native` where relevant.
- Review the rendered result at desktop and narrow/mobile widths. Check hierarchy, text wrapping, contrast, keyboard focus, empty/loading/error states, touch targets, and motion. Fix visible problems before delivery.
- Report the result and any remaining limitation briefly. User instructions and project requirements take precedence over suggestions from any source.
