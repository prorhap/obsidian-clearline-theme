# Clearline Theme Design Notes

This document is a quick reference for why the theme was built this way.

## Reference points

- **Minimal**: Clean base tone with reduced distractions
- **Primary**: Subtle sidebar tinting that pushes the main workspace forward
- **AnuPpuccin**: Fine-grained variables and broad UI coverage
- **Things**: Mac/iOS-native-feeling pills, tags, checkboxes, and card surfaces

## Visual goals

- Very bright, clean main canvas
- Soft-toned sidebar
- Blue active states
- Pill-shaped tags/properties
- Outline-friendly whitespace for readability
- Tables/callouts that surface context without heavy decoration

## Implementation intentions

1. **Background is near-white**
   - The note body should be the first thing your eye lands on

2. **Sidebar is subtly separated**
   - Recedes behind the body for a layered feel

3. **Active / selected states use soft blue**
   - A clear but gentle active cue

4. **Tags and properties are pills**
   - A natural way to present info tokens in Obsidian

5. **Tables / callouts / search results are card-styled**
   - To evoke visual tidiness and grouping

## Limitations

This theme is purely **style**.  
It does not attempt to reproduce:

- Semantic tagging
- Node-based data structures
- Dynamic view toolbar behavior
- Cards / calendar / table interaction models

## Recommended usage

- The closest impression is in **Light mode**
- Prefer **Show ribbon off**
- Setting properties to visible makes it look much more convincing
- Using this as a full theme is more stable than layering it over another heavy theme
