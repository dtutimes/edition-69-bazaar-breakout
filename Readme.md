## Bazaar Breakout (Edition 69)

A MakeCode Arcade project built with TypeScript and PXT modules.

### Setup Guide

- **Prerequisites:** Install Node.js (LTS) and the MakeCode `pxt` CLI (`npm install -g pxt`). VS Code recommended.
- **Install deps:** Use the workspace task or run:

  ```bash
  pxt install
  ```

- **Build locally:**

  ```bash
  pxt build --local
  ```

- **Deploy/run locally:**

  ```bash
  pxt deploy --local
  ```

- **Clean artifacts:**

  ```bash
  pxt clean
  ```

- **VS Code tasks:** You can also trigger `pxt install`, `pxt build`, `pxt deploy`, and `pxt clean` via the built-in tasks (Terminal → Run Task) configured for this workspace.

### Tech Stack

- **MakeCode Arcade (PXT):** Game runtime and tooling.
- **TypeScript:** Primary language (`main.ts`, modules in `pxt_modules/`).
- **PXT Modules:** Reusable libraries like `arcade-sprite-util`, `arcade-story`, `arcade-block-objects`, and others.
- **Assets:** Images, tilemaps, and generated resources (`images.g.*`, `tilemap.g.*`, `assets/`).
- **Build Artifacts:** Output in `built/` (e.g., `binary.js`).

### Contributors

- [Vyom Raturi](https://github.com/VyomRaturi)
- [Pushkar Dev](https://github.com/pushkardev123)
- [Ramanjot Singh](https://github.com/Raman-pro)