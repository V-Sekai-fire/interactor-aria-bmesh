# interactor-aria-bmesh

An Elixir library that holds n-gon meshes as vertices, edges, face-corner loops and faces, and walks the topology between them.

## What it is for

A face may have any number of sides and an edge may border any number of faces, so non-manifold geometry is representable. Per-corner attributes such as texture coordinates live on the loops, and `AriaBmesh.Topology` navigates the connectivity.

## Build

```sh
mix compile
```

Another Mix project uses it as a git dependency on this repository.

## Licence

MIT, as the SPDX headers and `mix.exs` state. There is no licence file.
