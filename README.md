<div align="center">
  <a href="https://duneui.dev/icons" target="_blank" rel="noreferrer">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./assets/duneui-icons-logo-white.svg" />
      <source media="(prefers-color-scheme: light)" srcset="./assets/duneui-icons-logo-black.svg" />
      <img alt="DuneUI Icons" src="./assets/duneui-icons-logo-black.svg" width="520" style="max-width: 100%;" />
    </picture>
  </a>

  <p><strong>Sculpted 24×24 geometric SVG icons from the DuneUI ecosystem.</strong></p>
  <p>
    An open-source library of <strong>606 precision SVG glyphs</strong> across <strong>16 categories</strong> and <strong>3 visual styles</strong> (<strong>1,818 standalone SVG files</strong>)—crafted with rounded optical balance, duotone depth, and editorial two-tone accents. Zero runtime lock-in, framework agnostic, copy and paste ready.
  </p>

  <p>
    <a href="https://duneui.dev/icons">Explore Interactive Gallery</a>
    &nbsp;·&nbsp;
    <a href="./CATALOG.md">Full Icon Catalog</a>
    &nbsp;·&nbsp;
    <a href="./catalog.json">JSON Manifest</a>
    &nbsp;·&nbsp;
    <a href="https://duneui.dev">DuneUI</a>
  </p>
</div>

---

## Highlights

- **606 Unique Glyphs · 1,818 SVG Files** — Every icon is exported cleanly across all three styles (**Stroke**, **Duotone**, and **Two-Tone**) with zero missing variants.
- **16 Curated Categories** — Organized into dedicated folders (`interface`, `development`, `ai-and-data`, `design`, `commerce`, `security`, and more) for effortless browsing and automation.
- **24×24 Optical Grid** — Consistent `viewBox="0 0 24 24"`, `stroke-width="1.75"`, and `round` line caps/joins for crisp rendering at `16px`, `20px`, `24px`, `32px`, and beyond.
- **Theme-Aware by Default** — Built with `currentColor` so icons adapt automatically to light mode, dark mode, and any Tailwind CSS or custom color token.
- **Machine-Readable Catalog** — Ships with [`catalog.json`](./catalog.json) (names, categories, tags, layer flags, and exact file paths) and [`CATALOG.md`](./CATALOG.md).
- **Stack Agnostic & Zero Lock-In** — Pure, standards-compliant SVG files that drop directly into HTML, React, Next.js, Vue, Nuxt, Svelte, Astro, Figma, or any design tool.

---

## Visual Styles

Every icon in this repository is available in **3 styles**:

| Style | Folder | Description |
| :--- | :--- | :--- |
| **Stroke** | [`icons/stroke/`](./icons/stroke) | Clean monochrome outline icons using `stroke="currentColor"`. |
| **Duotone** | [`icons/duotone/`](./icons/duotone) | Adds a subtle `currentColor` depth fill layer (`fill-opacity="0.14"`). |
| **Two-Tone** | [`icons/two-tone/`](./icons/two-tone) | Editorial two-tone look with DuneUI terracotta (`#B5542D`) accents and fill (`fill-opacity="0.16"`). |

---

## Categories Overview

All **606 icons** are organized into **16 category folders** inside each style directory:

| Category | Folder | Icons | Stroke | Duotone | Two-Tone |
| :--- | :--- | :---: | :---: | :---: | :---: |
| **Interface** | `interface` | 62 | [Browse](./icons/stroke/interface) | [Browse](./icons/duotone/interface) | [Browse](./icons/two-tone/interface) |
| **Development** | `development` | 61 | [Browse](./icons/stroke/development) | [Browse](./icons/duotone/development) | [Browse](./icons/two-tone/development) |
| **Design** | `design` | 45 | [Browse](./icons/stroke/design) | [Browse](./icons/duotone/design) | [Browse](./icons/two-tone/design) |
| **Lifestyle** | `lifestyle` | 45 | [Browse](./icons/stroke/lifestyle) | [Browse](./icons/duotone/lifestyle) | [Browse](./icons/two-tone/lifestyle) |
| **Navigation** | `navigation` | 43 | [Browse](./icons/stroke/navigation) | [Browse](./icons/duotone/navigation) | [Browse](./icons/two-tone/navigation) |
| **Commerce** | `commerce` | 39 | [Browse](./icons/stroke/commerce) | [Browse](./icons/duotone/commerce) | [Browse](./icons/two-tone/commerce) |
| **AI & Data** | `ai-and-data` | 35 | [Browse](./icons/stroke/ai-and-data) | [Browse](./icons/duotone/ai-and-data) | [Browse](./icons/two-tone/ai-and-data) |
| **Communication** | `communication` | 35 | [Browse](./icons/stroke/communication) | [Browse](./icons/duotone/communication) | [Browse](./icons/two-tone/communication) |
| **Files** | `files` | 34 | [Browse](./icons/stroke/files) | [Browse](./icons/duotone/files) | [Browse](./icons/two-tone/files) |
| **Time & Weather** | `time-and-weather` | 34 | [Browse](./icons/stroke/time-and-weather) | [Browse](./icons/duotone/time-and-weather) | [Browse](./icons/two-tone/time-and-weather) |
| **Media** | `media` | 33 | [Browse](./icons/stroke/media) | [Browse](./icons/duotone/media) | [Browse](./icons/two-tone/media) |
| **Devices** | `devices` | 31 | [Browse](./icons/stroke/devices) | [Browse](./icons/duotone/devices) | [Browse](./icons/two-tone/devices) |
| **Security** | `security` | 29 | [Browse](./icons/stroke/security) | [Browse](./icons/duotone/security) | [Browse](./icons/two-tone/security) |
| **Users** | `users` | 28 | [Browse](./icons/stroke/users) | [Browse](./icons/duotone/users) | [Browse](./icons/two-tone/users) |
| **Productivity** | `productivity` | 26 | [Browse](./icons/stroke/productivity) | [Browse](./icons/duotone/productivity) | [Browse](./icons/two-tone/productivity) |
| **Shapes** | `shapes` | 26 | [Browse](./icons/stroke/shapes) | [Browse](./icons/duotone/shapes) | [Browse](./icons/two-tone/shapes) |
| **Total** | **16 categories** | **606** | **606 SVGs** | **606 SVGs** | **606 SVGs** |

See [`CATALOG.md`](./CATALOG.md) for the complete alphabetical listing of every icon by category.

---

## Repository Structure

```text
.
├── assets/
│   ├── duneui-icons-logo-black.svg   # Brand wordmark (light mode)
│   └── duneui-icons-logo-white.svg   # Brand wordmark (dark mode)
├── icons/
│   ├── stroke/
│   │   ├── ai-and-data/
│   │   ├── commerce/
│   │   ├── communication/
│   │   ├── design/
│   │   ├── development/
│   │   ├── devices/
│   │   ├── files/
│   │   ├── interface/
│   │   ├── lifestyle/
│   │   ├── media/
│   │   ├── navigation/
│   │   ├── productivity/
│   │   ├── security/
│   │   ├── shapes/
│   │   ├── time-and-weather/
│   │   └── users/
│   ├── duotone/
│   │   └── <category>/<icon-name>.svg
│   └── two-tone/
│       └── <category>/<icon-name>.svg
├── catalog.json                      # Full metadata & file path manifest
├── CATALOG.md                        # Complete categorized icon index
└── README.md
```

---

## Basic Usage

### Inline SVG (HTML / Tailwind CSS)

Copy any `.svg` file from `icons/<style>/<category>/` (or from [duneui.dev/icons](https://duneui.dev/icons)) and style it with Tailwind utilities or standard CSS:

```html
<!-- icons/duotone/interface/check-circle.svg -->
<svg
  xmlns="http://www.w3.org/2000/svg"
  width="24"
  height="24"
  viewBox="0 0 24 24"
  fill="none"
  stroke="currentColor"
  stroke-width="1.75"
  stroke-linecap="round"
  stroke-linejoin="round"
  class="size-6 text-neutral-900 dark:text-neutral-100"
>
  <path d="M12 21a9 9 0 1 0 0-18 9 9 0 0 0 0 18Z" stroke="none" fill="currentColor" fill-opacity="0.14" />
  <path d="M12 21a9 9 0 1 0 0-18 9 9 0 0 0 0 18Z" />
  <path d="M8.5 12.3 10.8 14.6 15.8 9.4" />
</svg>
```

### React / JSX

Convert `stroke-width`, `stroke-linecap`, `stroke-linejoin`, and `fill-opacity` to camelCase:

```tsx
export function CheckCircleIcon(props: React.SVGProps<SVGSVGElement>) {
  return (
    <svg
      xmlns="http://www.w3.org/2000/svg"
      width={24}
      height={24}
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      strokeWidth={1.75}
      strokeLinecap="round"
      strokeLinejoin="round"
      {...props}
    >
      <path d="M12 21a9 9 0 1 0 0-18 9 9 0 0 0 0 18Z" stroke="none" fill="currentColor" fillOpacity="0.14" />
      <path d="M12 21a9 9 0 1 0 0-18 9 9 0 0 0 0 18Z" />
      <path d="M8.5 12.3 10.8 14.6 15.8 9.4" />
    </svg>
  )
}
```

### Programmatic Access via `catalog.json`

Use [`catalog.json`](./catalog.json) to build custom icon pickers, code generators, or sprite sheets:

```js
import catalog from './catalog.json' with { type: 'json' }

const securityIcons = catalog.icons.filter((icon) => icon.categorySlug === 'security')
console.log(securityIcons[0])
// {
//   name: "fingerprint",
//   category: "Security",
//   categorySlug: "security",
//   tags: ["biometric", "auth", "touch", "id"],
//   hasDuotone: true,
//   hasAccent: true,
//   files: {
//     stroke: "icons/stroke/security/fingerprint.svg",
//     duotone: "icons/duotone/security/fingerprint.svg",
//     "two-tone": "icons/two-tone/security/fingerprint.svg"
//   }
// }
```

> [!NOTE]
> This repository distributes raw, self-contained SVG assets rather than a runtime npm package—copy only the glyphs you need or automate imports directly from `icons/` and `catalog.json`.

---

## Contributing

Contributions that fix SVG geometry bugs, malformed paths, or visual alignment issues are welcome.

> [!NOTE]
> New icon designs follow strict DuneUI geometric rules (24×24 grid, 1.75px stroke, optical balance). If you need a new icon, feel free to open a discussion or issue describing the use case.

---

## License

This library is open-source and licensed under the **MIT License**.
