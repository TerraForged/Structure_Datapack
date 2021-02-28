# Structure_Datapack

Edit the [overworld.json file](https://github.com/TerraForged/Structure_Datapack/blob/main/data/minecraft/worldgen/noise_settings/overworld.json) to include the mod structures that you want to add with the desired separation settings.

Add the edited datapack using the datapack selection screen in the Create World menus, or add to your `config/terraforged/datapacks` folder.

### Notes on the settings:

| Name | Valid_Value_Range | Unit | Description |
| ---- | ---- | ---- | :---- |
| salt | `0` - `2147483647` | None | Used as to seed the randomization of structure positions. |
| spacing | `0` - `4096` | Chunks | Controls the size of the grid used to generate the structure. One structure will be placed randomly in each grid cell. |
| separation | `0` < `spacing` | Chunks | Controls the minimum distance to maintain between the random structure positions. Low values produce more random distribution but may result in structures appearing closer together sometimes. |
