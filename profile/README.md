![ScotMesh](https://raw.githubusercontent.com/ScotMesh/branding/main/social/readme-header.png)

ScotMesh is Scotland's off-grid radio mesh community. We run three networks side by side, **MeshCore**, **Meshtastic** and **Reticulum**, along with the tools and infrastructure that keep them going. Live tools and services are at **[scotmesh.net](https://scotmesh.net)**.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ScotMesh/branding/main/networks/reticulum/lockup-stacked-on-dark.png">
  <img src="https://raw.githubusercontent.com/ScotMesh/branding/main/networks/reticulum/lockup-stacked-on-light.png" height="48" alt="scotmesh/reticulum">
</picture>

### Reticulum

| Repo | What it is |
| --- | --- |
| [scotmesh-flasher](https://github.com/ScotMesh/scotmesh-flasher) | Browser flasher for RNode radios and standalone microReticulum nodes, live at [rnode.scotmesh.net](https://rnode.scotmesh.net) |
| [microReticulum_Firmware](https://github.com/ScotMesh/microReticulum_Firmware) | Our build of attermann's standalone Reticulum node firmware, for the boards people here actually deploy |
| [microReticulum](https://github.com/ScotMesh/microReticulum) | The Reticulum stack the firmware is built on, with our memory fixes for long-running solar nodes |
| [microStore](https://github.com/ScotMesh/microStore) | Embedded key-value store used by the firmware, with QSPI flash support |
| [RNS_Over_Meshcore](https://github.com/ScotMesh/RNS_Over_Meshcore) | Carries Reticulum over existing MeshCore networks using binary payloads |
| [RNS_Over_Meshtastic](https://github.com/ScotMesh/RNS_Over_Meshtastic) | The same over Meshtastic hardware |
| [rns.scotmesh.net](https://github.com/ScotMesh/rns.scotmesh.net) | The page for our public transport node, `rns.scotmesh.net:4242` |
| [scotmesh-chat](https://github.com/ScotMesh/scotmesh-chat) | One Conversation, 3 doors |


<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ScotMesh/branding/main/networks/meshtastic/lockup-stacked-on-dark.png">
  <img src="https://raw.githubusercontent.com/ScotMesh/branding/main/networks/meshtastic/lockup-stacked-on-light.png" height="48" alt="scotmesh/meshtastic">
</picture>

### Meshtastic

| Repo | What it is |
| --- | --- |
| [RepeaterTastic](https://github.com/ScotMesh/RepeaterTastic) | A Meshtastic hub with multi-radio, multi-identity, multi-mqtt, and plugin support |
| [repeatertastic-plugins](https://github.com/ScotMesh/repeatertastic-plugins) | The plugin store: what turns up under **Plugins → Browse store**, and where to list your own |
| [RepeaterTastic-MeshFlow](https://github.com/ScotMesh/repeatertastic-meshflow) | A RepeaterTastic plugin to publish to MeshFlow |
| [RepeaterTastic-HomeAssistant](https://github.com/ScotMesh/repeatertastic-homeassistant) | A RepeaterTastic plugin that puts your site and the nodes you pick into Home Assistant over MQTT |

Since v0.4.0 plugins are found, installed and updated from the GUI. Anyone can
list a plugin in the store: open a pull request on
[repeatertastic-plugins](https://github.com/ScotMesh/repeatertastic-plugins), or
point `plugins.store_url` at a store of your own.

Setup guides are on the [community wiki](https://wiki.scotmesh.uk/en/Meshtastic/Meshtastic).

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ScotMesh/branding/main/networks/meshcore/lockup-stacked-on-dark.png">
  <img src="https://raw.githubusercontent.com/ScotMesh/branding/main/networks/meshcore/lockup-stacked-on-light.png" height="48" alt="scotmesh/meshcore">
</picture>

### MeshCore

Live network tools: [CoreScope](https://corescope.scotmesh.net), [Live Map](https://map.scotmesh.net), [HopReach coverage](https://coverage.scotmesh.net) and [HopReact alerts](https://alerts.scotmesh.net).


### Everything else

| Repo | What it is |
| --- | --- |
| [scotmesh.net](https://github.com/ScotMesh/scotmesh.net) | The tools and services hub |
| [branding](https://github.com/ScotMesh/branding) | Logo, colours, type and graphics for every platform. Guidelines at [scotmesh.github.io/branding](https://scotmesh.github.io/branding/) |
| [scotmesh-wiki](https://github.com/ScotMesh/scotmesh-wiki) | Source for [wiki.scotmesh.uk](https://wiki.scotmesh.uk/) |

### Join in

[Discord](https://discord.gg/ytxfyuDmSt) · [Forum](https://scotmesh.uk) · [Facebook group](https://www.facebook.com/groups/26406719398968062) · [MeshCore & Meshtastic wiki](https://wiki.scotmesh.uk/) · [Reticulum wiki](https://wiki.scotmesh.net)
