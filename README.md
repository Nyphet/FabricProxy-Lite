# FabricProxy-Lite

Same as [FabricProxy](https://github.com/OKTW-Network/FabricProxy) but only support velocity and using Fabric-API handle
velocity packet.

This will have the better compatibility with other mods.

## Important

This is a modified version of the original FabricProxy-Lite made to work with Floodgate and LuckPerms to fix a bug that prevented Bedrock players to have custom skins.

## Setup

* Download mod
* Start server to generate config
* Setting velocity `player-info-forwarding-mode` to `modern` and `forwarding-secret`
* Setting `secret` in `config/FabricProxy-Lite.toml` match velocity config
