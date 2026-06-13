# Clearline Theme Design Notes

This document is a quick reference for why the theme was built this way.

## Core idea

**The page should yield to your writing.** Every decision is measured against
one question: does this help the body text lead, or does it compete with it?
When the two conflict, the interface gives way.

## Visual goals

- Very bright, clean main canvas
- Soft-toned sidebar that recedes behind the body
- Restrained blue active states
- Quiet, borderless metadata with clear key → value hierarchy
- Soft purple links and value tokens
- Outline-friendly whitespace for readability
- Tables/callouts that surface context without heavy decoration

## Implementation intentions

1. **Background is near-white**
   - The note body should be the first thing your eye lands on

2. **Sidebar is subtly separated**
   - Recedes behind the body for a layered feel

3. **Active / selected states use soft blue**
   - A clear but gentle active cue

4. **Properties recede instead of competing**
   - Borderless rows, no card, faint keys against readable values — metadata
     supports the note rather than announcing itself above it

5. **Tables / callouts / search results are lightly card-styled**
   - To evoke visual tidiness and grouping without heavy chrome

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
