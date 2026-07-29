# FEMEntity

A deformable solid simulated by the FEM solver. Its render geometry is separate from the geometry it simulates: each sub-mesh of the morph becomes one `FEMVisGeom` carrying that sub-mesh's own surface and UVs, so a multi-material asset keeps its authored appearance, while the simulation runs on a single welded mesh of their vertices. `FEMVisGeom.sim_verts_idx` maps each render vertex to the simulated vertex that drives it.

## FEMEntity

```{eval-rst}
.. autoclass:: genesis.engine.entities.fem_entity.FEMEntity
    :members:
    :undoc-members:
    :show-inheritance:
```

## FEMVisGeom

```{eval-rst}
.. autoclass:: genesis.engine.entities.fem_entity.FEMVisGeom
    :members:
    :undoc-members:
    :show-inheritance:
```
