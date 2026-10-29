# Selections

A selection picks the links, geoms or vertices of an entity that a set of scoped options applies to. It keys the `links`, `geoms` and `vertices` mappings of the entity options: `gs.LinkIndex` picks links by name or glob pattern, `gs.GeomIndex` picks the collision geoms of a link by their ordinal in the asset, and `gs.VertexIndex` picks the vertices of a deformable entity by ordinal or by position. For how scoped options combine with the entity options, see {doc}`/user_guide/configuration/entity_options`.

## LinkIndex

```{eval-rst}
.. autoclass:: genesis.options.indices.LinkIndex
    :members: named
```

## GeomIndex

```{eval-rst}
.. autoclass:: genesis.options.indices.GeomIndex
    :members: at, all
```

## VertexIndex

```{eval-rst}
.. autoclass:: genesis.options.indices.VertexIndex
    :members: at, in_box, closest_to, __or__
```
