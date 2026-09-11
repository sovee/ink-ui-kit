# Ink UI Kit

[中文](README.zh-CN.md)

A one-colour CSS component kit for apps that talk to e-paper displays. Pure black on warm off-white, a heavy 2px border as the signature, pill controls, and a panel component that renders like a 1-bit screen.

## Usage

Drop `ink-ui-kit.css` into your project and wrap your page (or root element) in `.ink-root`:

```html
<link rel="stylesheet" href="ink-ui-kit.css" />
<body class="ink-root">
  <button class="ink-btn ink-btn--primary">Primary</button>
</body>
```

Open [index.html](index.html) for a full, self-contained reference page showing every color, type style, and component.

## What's included

- **Colors** — an 8-step monochrome scale, `--ink-black` through `--ink-white`
- **Typography** — a grotesk UI face, a serif for quoted text, and a mono for numerics
- **Spacing & radius** — an 8px-rooted spacing scale and sharp/soft/pill corner treatments
- **Components** — buttons, chips, badges & tags, cards, the signature e-ink panel, lists, empty states, and a tab bar
- **Utility classes** — small helpers for color, border, spacing, and layout

All classes are prefixed `ink-` so the kit won't collide with existing styles.

## Files

- `ink-ui-kit.css` — the standalone stylesheet
- `index.html` — offline demo/reference page
- `artifact.html` — the same reference content, structured for publishing as a Claude Artifact
