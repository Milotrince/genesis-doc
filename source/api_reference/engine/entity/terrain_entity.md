# TerrainEntity

The entity `scene.add_entity(gs.morphs.Terrain(...))` returns: a rigid entity whose single fixed link is a height field, a grid of elevations that bodies rest on and that answers a height query at any point. For usage, see {doc}`/user_guide/physics/terrain`.

```{eval-rst}
.. autoclass:: genesis.engine.entities.rigid_entity.terrain_entity.TerrainEntity
    :members:
    :undoc-members:
    :show-inheritance:
```

## See also

- {doc}`/user_guide/physics/terrain`: building a terrain and querying its surface height.
- {doc}`/api_reference/engine/entity/morph/file_morph/terrain`: the `gs.morphs.Terrain` morph and its options.
