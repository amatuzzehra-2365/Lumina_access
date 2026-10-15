# Lumina Access

An interactive, single-file workshop for learning web accessibility. Practice keyboard navigation, color contrast, and WCAG 2.1 auditing in your browser, with no installs or dependencies.

**Live demo:** https://amatuzzehra-2365.github.io/Lumina_access/

## What's inside

The app has four modules:

1. **Keyboard and ARIA:** try tabs, an accordion, a modal dialog, a menu button and an accessible form, with a live keyboard event log.
2. **Contrast and zoom:** a WCAG contrast checker with a "suggest a passing color" tool, plus a magnification stage with reflow, text-spacing and color-vision simulations.
3. **Fix the UI:** a broken "Before" sample and a fixed "After" sample, with a 17-item issue tracker that shows how to detect and fix each problem.
4. **Audit report and checklist:** rate WCAG success criteria, then generate, copy, print or download (CSV) your audit report.

## Comfort and vision settings

A built-in panel for people with different sensory and cognitive needs:

- **Presets:** focus support (ADHD), sensory-calm (autism, sensory sensitivity), easier reading (dyslexia), color-vision safe (color blindness), and low vision
- **Fine-tune:** calm mode, focus mode, wider spacing, a blue/orange palette, a reading ruler and text size up to 150%
- **Themes:** Light, Dark, Sepia and High contrast
- Calm mode turns on automatically if your device is set to reduce motion

Presets are starting points, since everyone's needs differ.

## Features

- Single HTML file, works offline
- Keyboard-friendly, with a skip link, visible focus and a roving-tabindex tablist
- Progress, notes, theme and comfort settings are saved in your browser (localStorage)
- Export your audit as text or CSV

## Run it

Open `index.html` in any modern browser. No build step is needed.

To host it on GitHub Pages: **Settings, then Pages, then Deploy from a branch, then main / root**.

## Limitations

This tool can't replace testing with real assistive technology such as NVDA, JAWS, VoiceOver or TalkBack. Its scanners check only what they can compute, and the color-vision filters are simulations.

## Browser support

Current versions of Chrome, Edge, Firefox and Safari. Saved progress needs localStorage to be enabled.

## License

MIT. See `LICENSE`.
