# Changelog

## Modular Character Preview Version 1.0 - Initial Release

This version introduces the Modular Character Preview Component, a lightweight and extensible Blueprint system for Unreal Engine that provides real-time character preview rendering with full modular support.

### Core Functionality

- **Scene Capture Integration**
  - Renders character previews to UI using a dedicated SceneCapture2D.
  - Supports isolated lighting for consistent, high-fidelity visuals in the UI.

- **Mesh Visibility Synchronization**
  - Automatically reflects the character’s mesh visibility states in the preview.
  - Ensures accurate representation of equipped gear, including conditional hiding (e.g., facial grooms hidden by helmets).

- **Modular Component Design**
  - Blueprint-only implementation with clear, extendable logic.
  - Designed to drop into any character Blueprint with minimal setup.

- **Equipment Preview Support**
  - Displays modular skeletal mesh parts such as armor, clothing, accessories, and weapons. (Static Meshes will be added later)
  - Supports skeletal mesh attachments, and animation states. (Grooms/Metahuman support coming soon)

- **UI Integration**
  - Includes optional controls for animation selection and reset functionality.
  - Toggle for mouse-based rotation and preview movement for interactive UIs.

- **Performance Optimization**
  - Tick control ensures the component is only active when needed.
  - Lightweight Blueprint graph with reduced overhead.

- **Multiplayer Compatibility**
  - Safe for use in replicated environments with auto detection.
  - Supports accurate preview behavior in multiplayer character screens.

### Known Compatibility

- Verified on Unreal Engine 5.4, 5.5 and 5.6.
- Supports both single-player and networked (replicated) projects.

### Intended Use Cases

- RPG inventory and equipment systems
- Character customization interfaces
- Marketplace-style gear previews
- Loadout configuration screens

This release is focused on delivering a clean and efficient foundation with all essential features required for gear preview and modular character visualization. Future updates will expand compatibility, add more configuration options, and introduce example integrations.
