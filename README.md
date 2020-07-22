# HTN planning demo project

This is the demo project for my upcoming HTN planning plugin for Unreal Engine 4.

To download the latest version, grab a release from [here](https://github.com/maksmaisak/htn-example-project/releases).
Requires the HTN plugin.

Also check out the [documentation website](https://maksmaisak.github.io/htn/#/).

## Contents

There are two maps in the project: `SimpleTest` and `TacticsTest` showing different use cases for the plugin.

### SimpleTest

**Where to find**: `Content/HTNExampleProject/Maps/SimpleTest`

[Video](https://youtu.be/ARJzKhosmEI)

In this map a single character needs to shoot at target, but doesn't have a gun or ammo.
There are multiple guns and ammo crates in the map, and the character invents the optimal plan to get what they need and shoot the target.

A more thorough explanation is available at the [documentation website](https://maksmaisak.github.io/htn/#/README?id=a-simple-example)

### TacticsTest

**Where to find**: `Content/HTNExampleProject/Maps/TacticsTest`

[Video](https://youtu.be/FHapYbv9vjE)

In this map two groups of characters fight in a simplistic FPS arena using guns and grenades.
They use [EQS queries](https://maksmaisak.github.io/htn/#/eqs) during planning to consider tactical paths through the map and stay in cover while they get into shooting range.
They update their plans continuously as battlefield conditions change using [Services](https://maksmaisak.github.io/htn/#/service).

## Ackgnowledgements

This example project uses the [Advanced Locomotion System](https://www.unrealengine.com/marketplace/en-US/product/advanced-locomotion-system-v1) by LongmireLocomotion.

