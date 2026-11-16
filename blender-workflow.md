# Blender workflow for house plans (PC)
Verify add-on/version details at blender.org; I'm not certain of every setting.

1. Set units: Metric, 1 unit = 1 m (Scene properties).
2. Plan view: top orthographic (Numpad 7). Draw walls as extruded planes/meshes to real sizes
   (typical wall 0.2 m thick, room heights ~2.7-3.0 m - confirm with your own standards).
3. Add doors/windows with a reusable asset library (build once, reuse).
4. Optional: BlenderBIM add-on for proper building elements (learning curve; test first).
5. Output a 2D floor plan: ortho top view, render with clean line/flat shading, add dimensions/labels
   (add labels in a free editor like Inkscape/LibreCAD or Blender text).
6. 3D: add basic materials, sun light, camera; render stills first (Eevee is faster, Cycles is nicer but slower).
7. Time-lapse: screen-record while drafting; speed up in CapCut/DaVinci Resolve (free).
8. Export: PDF plan pack (plans, elevations, 3D images) + watermark until paid.
Save a TEMPLATE .blend file with units, camera, lights, materials ready for every new plan.
