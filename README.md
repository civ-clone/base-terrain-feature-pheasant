# base-terrain-feature-pheasant

The `Pheasant` terrain feature: a special resource a square can hold.

For example: Civ2's Pheasant, found on Forest.

This package only declares the class: it has no `main` and registers nothing, so installing it changes no game.
A game's rules register it and give it its yields.

```ts
import Pheasant from '@civ-clone/base-terrain-feature-pheasant/Pheasant';
import { instance as availableTerrainFeatureRegistryInstance } from '@civ-clone/core-terrain-feature/AvailableTerrainFeatureRegistry';

availableTerrainFeatureRegistryInstance.register(Pheasant);
```

Part of the Civ2 work (civ-clone/web-renderer#1008).
