# Installation

1. Enable the plugin in your project.
![Enable plugin](../images/step-01-enable-plugin.png)
2. Add `BPI_ModularCharacterPreview` to your character and implement `GetMeshes`.
![Add BPI and implement GetMeshes](../images/step-02-add-bpi%20and%20GetMeshes.png)
3. Add the `BPC_ModularCharacterPreview` component to your Player Controller.
![Add component to Player Controller](../images/step-04-add-component-to-player-controller.png)
4. Add `W_ModularCharacterPreview` to your UI widget (inventory, equipment, etc.).
![Add widget](../images/step-05-add-widget.png)
5. In the widget, disconnect the static preview texture binding so the runtime RenderTarget can be assigned.
![Disconnect static binding](../images/step-06-add-widget-disconnect-this-connection.png)

Notes:
The `GetMeshes` output should return Main Mesh, Follower Meshes array, Face Mesh, and Groom Components array.
