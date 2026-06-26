# Hokkaido Summer Family Field Guide

## Design Direction

This redesign treats the travel guide as a premium family field guide for a summer Hokkaido trip: part travel magazine, part route notebook, part postcard set. The visual language should feel outdoorsy, warm, and organized rather than like a dashboard.

## Visual System

- Palette: lavender purple `#8f79bd`, lake blue `#4aa7c7`, milk cream `#fff7e6`, corn yellow `#f2bf4a`, pine green `#1f5f48`, soft coral `#e77f6f`.
- Background language: soft contour lines, route traces, field-grid texture, pale ticket paper, light postal marks. Patterns must stay low contrast for readability.
- Typography: traditional Chinese readability first; serif display headings for magazine cover feeling, clean sans-serif body text for itinerary scanning.
- Cards: postcard and field-note treatment with small category badges, soft paper shadows, stable image ratios, and travel-note spacing.
- Motifs: each day receives a small contextual marker:
  - 7/10 Otaru: canal, glass, seafood market.
  - 7/11 Sapporo: shrine walk, park, Tanukikoji street.
  - 7/12 Shiroi Koibito: cookie workshop, sweets, Mt. Moiwa night view.
  - 7/13 Toyako transfer: lake, charter, onsen.
  - 7/14 Lake Toya: observatory, farm, ice cream.
  - 7/15 Airport: return, souvenirs.

## Layout Rules

- Preserve all itinerary content, dates, times, links, ticket counts, flight details, lodging, and existing interactions.
- Add visual identity through CSS and decorative elements only; do not rewrite the itinerary.
- Keep daily tabs horizontally scrollable on mobile.
- Maintain readable print output: remove decorative textures, shadows, and heavy backgrounds in print.

## Implementation Notes

- The original `hokkaido-travel-guide.html` remains unchanged.
- The themed version is `hokkaido-travel-guide-hokkaido-theme.html`.
- The new theme can use inline CSS decorations and existing assets; no existing `assets/` paths should be changed.
