# FAQ

**Q:** Can I disable UI elements?  
**A:** Yes. All UI preview options are customizable and can be changed in the component's Details tab on the Player Controller after following the Installation section.

**Q:** Does it support multiplayer?  
**A:** Yes. The preview is client-local and safe to use in multiplayer projects.

**Q:** Do I need to add tags to meshes?  
**A:** No. Tags are no longer required due to the new BPI implementation.

**Q:** What should `GetMeshes` return?  
**A:** Return the exact meshes you want shown in the preview. The Main Mesh should be the primary character mesh you want displayed. For example, in Game Animation Sample projects, use the mesh you want to see in the preview, not the UEFN mesh. Also return the Follower Meshes array, Face Mesh, and Groom Components array.

**Q:** Does it work when I possess another pawn?  
**A:** Yes. Keep the component on the Player Controller and make sure `GetMeshes` returns the original character’s meshes.
