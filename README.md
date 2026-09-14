# BLORP Main

Responsive frontend based on the supplied BLORP design reference. Open `index.html` directly or serve this directory with `python3 -m http.server 8000`.

## Included

- Reference-based landing page, reactor artwork, animated light trails and core glow.
- Model catalog, monthly/yearly pricing and plan-selection dialogs.
- Lab interface with model/mode selection, prompt handling and animated reasoning graph.
- Experiments, developer information, about and illustrative system-status screens.
- Responsive mobile layout, keyboard-operable controls, native accessible dialogs and reduced-motion support.

## Scope

This is a frontend preview. Chat replies explicitly indicate that no AI backend is connected. Sign-in does not authenticate. Pricing does not collect payments. Statistics and status values are illustrative figures from the reference. The reactor uses the supplied artwork with CSS animation overlays; it is not an independently rendered 3D model. Google Fonts are optional, with local font fallbacks. No build step or dependency installation is required.

## Repository

Source: https://github.com/mi24rizwan66-hash/blorp-main

`assets/reference.jpeg` is the user-supplied reference and is required for the hero artwork. Keep the asset alongside the source. Authentication, AI calls and payment verification require a server implementation before production use.
