# Changelog

All notable changes to Synthenis UI Kit will be documented in this file.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).  
This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.0.0] — 2025

### Added
- Design token system via CSS custom properties (`--accent`, `--bg`, `--surface`, `--border`, `--ease`, etc.)
- SYN typeface integration via Synthenis CDN with `font-display: swap`
- Typography scale — 6 levels from Display (40px/700) to Caption (11px/700/uppercase)
- Button components — Primary, Secondary, Accent, Danger variants in three sizes (sm, default, lg)
- Floating Action Button — 42×42px circular, accent background
- Input components — Text, Email, Search (icon-prefixed), Textarea with glass focus states
- Card component — glass surface, icon wrap, title, description, footer, badge
- Toggle component — 32×20px track, 16px thumb, instant state, cubic-bezier easing on thumb
- Checkbox component — 21×21px, 7px border-radius, accent fill on checked state
- Dropdown component — fixed-position via `getBoundingClientRect`, outside-click dismissal, selected state with checkmark
- Progress bar — accent fill, shimmer `::after` animation, eased width transition
- Toast notification system — auto-dismiss 10s, deduplication by type+message, slide-fade animation
- Installation support via CDN and git clone
- Full responsive layout — breakpoints at 768px and 480px
- Zero external dependencies