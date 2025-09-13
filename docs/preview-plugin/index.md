## Plugin Overview: Modular Character Preview Component

The Modular Character Preview Component is a lightweight, Blueprint-only system for Unreal Engine that enables real-time visual previews of characters with equipped gear. It is designed for use in inventory interfaces, character customization screens, and modular equipment systems. The component integrates with modular skeletal meshes and supports armor, clothing, hair, facial grooms, and animations.

This system renders the assembled character in a controlled lighting environment using a SceneCapture2D, allowing the preview to be displayed directly in the user interface. Mesh visibility in the preview is automatically synchronized with the visibility of the corresponding meshes on the character. For example, if a facial groom is hidden due to an equipped helmet on the main character, it will also be hidden in the preview. This ensures accurate representation of the equipped appearance.

The component is modular and extensible, with optimized tick control and optional support for multiplayer replication.

### Features

- Real-time character preview rendering in UI
- Visibility mirrors character mesh states
- Compatible with modular characters and skeletal meshes
- Supports equipment, grooms, and animation previews
- Controlled lighting for consistent visual output
- UI preview movement toggle for rotation (Can be toggled on or off)
- Clean, optimized Blueprint structure
- Multiplayer-safe with replication support
