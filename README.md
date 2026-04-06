# Clearline for Obsidian

Clearline is a clean, focused Obsidian theme.  
It focuses on **visual tone and interaction feel** — whitespace-driven layout, soft surfaces, and blue accents.

## What's included

- `Clearline/manifest.json` — Obsidian theme metadata
- `Clearline/theme.css` — Full theme file
- `Clearline/versions.json` — Version mapping file
- `clearline-snippet.css` — Same styles as a CSS snippet you can layer on top of any theme
- `Clearline-demo-note.md` — A demo note you can open right away to test the look

## Design direction

This theme aims for the following feel:

- Bright canvas with a very subtle blue-gray sidebar
- Rounded pill tags / properties / selected states
- Soft borders and whitespace-driven layout
- Blue active states
- Card-like tables / callouts / search results
- Natural system font feel on Mac

## Install option A — Full theme

1. Extract this archive.
2. Copy the `Clearline` folder into your vault's `.obsidian/themes/` directory.
3. In Obsidian, go to `Settings → Appearance → Themes`.
4. Select `Clearline` from the theme list.

### Folder structure must be exact

It should look like this:

```text
YourVault/
└── .obsidian/
    └── themes/
        └── Clearline/
            ├── manifest.json
            ├── theme.css
            └── versions.json
```

## Install option B — CSS snippet

1. Place `clearline-snippet.css` in your `.obsidian/snippets/` folder.
2. In Obsidian, go to `Settings → Appearance → CSS snippets`.
3. Click `Reload snippets`, then enable `clearline-snippet`.

### Recommended snippet usage

- The most predictable result is **Default theme + snippet**.
- If you're already using a heavy community theme, some styles may clash.
- In that case, **installing the full theme** is more stable than using the snippet.

## Recommended settings for the best look

These are **optional**.

- `Settings → Appearance → Base color scheme` = **Light**
- `Settings → Appearance → Show ribbon` = **Off**  
  (The vertical ribbon is visually the most distracting element — turning it off gives a cleaner look.)
- `Settings → Settings → Interface font / Text font` = Keep default  
  (The theme uses a Mac-friendly system font stack internally.)
- `Settings → Editor → Properties in document` = **Visible**
- Open one or two notes at a time rather than stacking many tabs

## What this theme covers

- Subtle sidebar separation
- Tag/property pills
- Blue active state accents
- Cleaner, more spacious body text
- Soft card-style tables/callouts

## What this theme does not cover

These are closer to **features** and can't be replicated with a theme alone.

- Semantic tagging systems
- Node/field-based data structures
- Outline-native manipulation
- Dynamic view toolbars / cards / calendar behavior
- Structured data models

## Quick-tweak values

Change these values at the top of `theme.css` or `clearline-snippet.css` to easily adjust the feel.

- `--cl-accent`
- `--cl-sidebar-tint`
- `--file-line-width`
- `--font-text-size`
- `--cl-radius`

## Troubleshooting

### Theme doesn't appear in the list
- Most likely the folder structure is wrong.
- It must be `/.obsidian/themes/Clearline/manifest.json`.

### Snippet doesn't appear in the list
- Click `Reload snippets`.
- Make sure the file extension is exactly `.css`.

### Feels too blue
- Change `--cl-accent` to a more grayish blue.
- Also reduce `--cl-accent-soft` and `--cl-accent-line` for a more muted look.

### Want more width
- Try setting `--file-line-width` to around `980px`.

## Note

This is an **independent theme** — not affiliated with or derived from any specific product.
