# Features

The Modular Character Preview Component provides a streamlined solution for previewing modular characters with equipped gear in real time. It is designed to be integrated quickly into existing UI systems with minimal setup.

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

## Groom Support

- Supports Groom Components (hair, beards) through the `GetMeshes` interface output.
- MetaHuman grooms may still require additional tuning depending on bindings and LOD settings.

## Performance-Conscious Design

- Blueprint-only implementation with clean and optimized logic.
- Tick logic is only active when necessary to reduce overhead.

## Multiplayer Compatibility

- Client-local preview rendering, safe for multiplayer equipment and loadout systems.
- No replication required for preview visuals.

## Customization Ready

- Fully modular and extensible Blueprint graphs.
- Can be extended or styled to match custom UI and game systems.
