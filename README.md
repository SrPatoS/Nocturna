# Nocturna 🌌

<!-- Plugin description -->
A modern, futuristic dark theme for JetBrains IDEs. Built with native support for the **Islands UI floaty layout**, featuring rounded endpoints, immersive workspaces, and borderless canvas flows.
<!-- Plugin description end -->

Nocturna blends readability and aesthetics together, optimized for modern editors like WebStorm, IntelliJ IDEA, and PhpStorm.

---

## ✨ Features

- 🏝️ **Islands UI Support**: Built to inherit from the floating-island design base without frame overlays.
- 🎨 **Vivid Visuals**: Colors are tuned to lower eye strain without sacrificing high contrast syntax logic.
- 📐 **Full Rounded Frames**: Adapts components and floating items seamlessly to the IDE base curve setup.

---

## 🚀 Installation

### 1. Traditional Download
Since this is a manual setup or starting project, you can compile and import it manually:

1. Run the build command inside the root folder:
   ```powershell
   .\gradlew buildPlugin
   ```
2. In your main IDE, navigate to `Settings (Ctrl+Alt+S)` -> `Plugins` -> `⚙️ Icon` -> `Install Plugin from Disk...`.
3. Select the distribution file available inside `/build/distributions/`.

---

## 🛠️ Setup & Running

To test and render this theme inside a temporary sandbox container:

```powershell
.\gradlew runIde
```

*Requires IntelliJ Platform 2024.3+ for full Floating Panel styling assets.*

---

## 🤝 Maintainer

Maintained and developed with care by **vaviz**. Feel free to fork and open feedback issues!
