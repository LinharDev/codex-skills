---
name: shadcn
description: Convenções do shadcn/ui para React + Tailwind
---

# Shadcn/UI

Ao usar shadcn/ui:
- Componentes via CLI: `npx shadcn@latest add [component]`
- Base: Radix UI primitives + Tailwind CSS
- Estilos em `components/ui/`
- Use `cn()` (clsx + tailwind-merge) para classes condicionais
- Tema via CSS variables em `globals.css`
- Form: react-hook-form + zod para validação
- Sempre verificar docs oficiais: ui.shadcn.com
