# Features

The Modular Character Preview Component provides a streamlined solution for previewing modular characters with equipped gear in real time. It is designed to be integrated quickly into existing UI systems with minimal setup.

## Quick Integration

- Requires only two main steps:
  1. Add the preview component to the Player Controller.
  2. Add the provided preview widget to any UI container (e.g., inventory or equipment screens).
- Minimal character setup required:
  - The main skeletal mesh must be assigned a tag for identification.
  - Optional: Add ignore tags to meshes that should never be shown in the preview (e.g., Character meshes used in live retargeting setups such as GASP UEFN Mesh).
- No additional initialization logic or custom character modifications needed.

## Real-Time Modular Preview

- Renders modular character assemblies, including armor, clothing, accessories, and weapons.
- Uses SceneCapture2D to deliver high-fidelity visuals directly into user interface widgets.
- Optional UI controls for preview movement, animation states, and reset functionality.

## Visibility Sync with Character Meshes

- Automatically reflects the visibility of modular parts on the actual character.
- Supports conditional hiding, such as facial hair when a helmet is equipped.

## Animation Preview Support

- Includes a built-in dropdown menu in the UI for selecting preview animations.
- Animation list is dynamically populated from a user-defined DataTable.
- Dropdown visibility can be toggled directly in the component's Details panel on the Player Controller.
- Allows clean integration with animation sets for idle, stance, or custom poses without additional scripting.

## Skeletal Mesh Compatibility

- Fully supports modular skeletal mesh setups for armor, clothing, and accessories.
- Designed for use with characters assembled from multiple skeletal mesh components.

## Groom Support (Planned)

- Partial support for groom components such as beards and hairstyles. (logic diconnected currently)
- Known issues exist with certain MetaHuman grooms not rendering consistently in the preview.
- Full groom compatibility is planned for a future update.

## Performance-Conscious Design

- Blueprint-only implementation with clean and optimized logic.
- Tick logic is only active when necessary to reduce overhead.

## Multiplayer Compatibility

- Replication-aware design ensures consistent previews in networked environments.
- Safe to use in multiplayer equipment and loadout systems.

## Customization Ready

- Fully modular and extensible Blueprint graphs.
- Can be extended or styled to match custom UI and game systems.
