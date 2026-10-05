# interactor-aria-bmesh

An Elixir library that holds n-gon meshes as vertices, edges, face-corner loops and faces, and walks the topology between them.

## What it is for

A face may have any number of sides and an edge may border any number of faces, so non-manifold geometry is representable. Per-corner attributes such as texture coordinates live on the loops, and `AriaBmesh.Topology` navigates the connectivity.

## Build

```sh
mix compile
```

Another Mix project depends on it from git:

```elixir
{:aria_bmesh, git: "https://github.com/V-Sekai-fire/interactor-aria-bmesh.git"}
```

## Licence

MIT, as the SPDX headers and `mix.exs` state. There is no licence file.
