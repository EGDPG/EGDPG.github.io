<details>
<summary><strong>Version 1.0 – Initial Release</strong></summary>

<br/>

This release introduces the Modular Character Preview Component, a lightweight and extensible Blueprint-only system for Unreal Engine. It provides real-time, UI-integrated character previews with modular mesh support and minimal setup requirements.

<br/><br/>

<b>Core Features</b>

<br/>

<b>Scene Capture Integration</b><br/>
• Renders real-time character previews directly into UI using a dedicated <code>SceneCapture2D</code><br/>
• Includes isolated lighting configuration for consistent, high-quality visual output

<br/><br/>

<b>Mesh Visibility Synchronization</b><br/>
• Automatically mirrors the visibility states of the character’s meshes<br/>
• Ensures accurate preview of equipped gear, including conditional hiding (e.g., facial grooms hidden by helmets or masks)

<br/><br/>

<b>Modular Component Design</b><br/>
• Blueprint-only implementation with a clean and extendable logic structure<br/>
• Drop-in component that requires no structural changes to the character class beyond tag assignments

<br/><br/>

<b>Equipment Preview Support</b><br/>
• Supports modular skeletal mesh components such as armor, clothing, accessories, and weapons<br/>
• Static Mesh support is planned for a future update<br/>
• Groom and MetaHuman compatibility is in progress and will be addressed in upcoming releases

<br/><br/>

<b>Animation Preview Integration</b><br/>
• Includes a dropdown animation selector populated from a user-defined DataTable<br/>
• Dropdown visibility can be toggled via the component’s Details panel in the Player Controller<br/>
• Reset functionality and interactive rotation controls are included in the preview widget

<br/><br/>

<b>UI Integration</b><br/>
• Designed for seamless embedding into existing inventory or equipment UI layouts<br/>
• Preview widget is modular and reusable across UI contexts

<br/><br/>

<b>Performance Optimization</b><br/>
• Tick logic is only active when the preview is in use<br/>
• Minimal runtime overhead due to efficient Blueprint graph structure

<br/><br/>

<b>Multiplayer Compatibility</b><br/>
• Replication-safe design with automatic detection and proper handling of networked characters<br/>
• Fully compatible with replicated loadout and equipment systems

<br/><br/>

<b>Compatibility</b><br/>
• Verified on Unreal Engine 5.4, 5.5, and 5.6<br/>
• Supports both single-player and multiplayer (replicated) projects

<br/><br/>

<b>Use Cases</b><br/>
• RPG inventory and equipment preview systems<br/>
• Character customization interfaces<br/>
• Marketplace-style gear presentation<br/>
• Loadout configuration and character setup screens

<br/><br/>

<b>Notes</b><br/>
This release delivers a robust foundation focused on performance, ease of integration, and visual consi
