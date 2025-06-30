# CAD

All design iterations are created using **FreeCAD 1.0.x**.

## Meshing

For export and simulation, I use the **Mesh Workbench** in FreeCAD with the following **Tessellation settings**:

- Surface deviation: **0.10 mm**
- Angular deviation: **3.00°**
- Meshing mode: **Standard**

Although the geometries are relatively simple, mesh generation can still take several seconds due to the number of fillets and surfaces.

## Modeling Notes

I make extensive use (and sometimes overuse) of the **Fillet** feature, which can be **fragile and sensitive** to changes in sketches.  
Modifying a side or top sketch may break downstream fillets, so caution is advised when editing.

This modeling workflow favors **rapid iteration** over parametric robustness.  
While not always fully representative of a final manufacturable part, it enables fast exploration of aerodynamic shaping ideas.
