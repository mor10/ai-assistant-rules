---
description: Instructions for how to install and use shadcn components
globs: *.tsx, components/ui/**/*.*
---
- Use shadcn/ui components for UI components
- Install new components using npx
- NEVER call `shadcn-ui@latest`
- ALWAYS call `shadcn@latest` and use the `--force` flag to ensure compatibility. Example:
npx shadcn@latest add button --force