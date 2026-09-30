# Project Guidelines

## Tailwind CSS v4
- **Always use standard Tailwind CSS v4 utilities** across all styling (sizing, spacing, colors, borders, typography, transforms, transitions, flexbox, and grid).
- **Avoid arbitrary bracket syntax** (`[...]`) whenever a standard or dynamic utility is supported.
- **Dynamic Spacing & Sizing Scale**: In Tailwind v4, utilities dynamically accept fractional and custom numbers calculated as `px / 4` or `rem / 0.25` (e.g., use `w-162.5` / `h-162.5` instead of `w-[650px]` / `h-[650px]`).
- **Color Opacity**: Use Tailwind's modern slash-alpha syntax (e.g., `bg-indigo-500/10`, `text-white/80`, `border-indigo-500/20`).
- **Gradients (Tailwind v4)**: Use Tailwind v4's linear gradient utilities `bg-linear-to-*` (e.g., `bg-linear-to-r`, `bg-linear-to-tr`, `bg-linear-to-br`) instead of legacy `bg-gradient-to-*`.
- **Standard Scale Tokens**: Prefer standard scale increments for typography, rounding, opacity, blur, and transforms (e.g., `rounded-xl`, `text-sm`, `blur-3xl`, `opacity-60`).
