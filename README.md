# Silicon Foundry — Transformer on Silicon

[![Besuche](https://hits.sh/github.com/kava140982-max/free.svg?label=Besuche)](https://hits.sh/github.com/kava140982-max/free/) · [🌐 Silicon Foundry im Browser öffnen](https://kava140982-max.github.io/free/)


An immersive, backend-free Three.js visualization of a transformer decoder rendered as GPU hardware. The experience moves from the external shroud through the board and SM array into a stylized tensor core.

## Controls

Drag to orbit. Scroll to dive. Use `1`–`4` for hardware layers, `+`/`-` for zoom, `T` for the guided tour, `R` to reset, and `Esc` to stop the tour. Touch devices use the same native orbit and pinch gestures.

## Run locally

Because this is a static ES-module page, serve the repository from a local HTTP server:

```bash
python3 -m http.server 3000
```

Then open `http://localhost:3000/` in a modern browser with hardware acceleration enabled.

Copyright © Kai Valenta. The demo is free to use; keep the visible attribution when sharing or adapting it. See [NOTICE.md](NOTICE.md).
