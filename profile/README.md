<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="haulnet-logo-on-dark.svg">
    <img src="haulnet-logo-on-light.svg" alt="Haulnet" height="64">
  </picture>
</p>

<p align="center"><b>Play R.E.P.O. with friends on a server you control.</b></p>

R.E.P.O. runs every online game through Photon Cloud, even when friends sit in the same room. Haulnet is a free,
open-source mod that lets the game live on your own PC, on a Haulnet server or on any server by address instead.
No Photon account, no admin rights, and until you pick Haulnet the game plays exactly as without the mod.

**Who it is for**

- **Players far from Photon's regions.** The game offers only Photon Cloud's regions; when none is close, every
  game has high ping. A Haulnet server can stand in any city (Moscow, Novosibirsk and Vladivostok today), and
  anyone can add one closer to their players.
- **People who want their own server.** Run haulnet-server on a VPS or at home, keep it for friends or list it for
  everyone.
- **Friends in the same room or on the same VPN.** With "On my PC" the host's PC is the server and friends connect
  straight to it, with no internet server in between.

| Repository | What it is |
|---|---|
| [haulnet-repo](https://github.com/haulnet/haulnet-repo) | The mod (BepInEx 5): host on your PC, play on Haulnet servers or any server by address, friends follow the Steam invite |
| [haulnet-server](https://github.com/haulnet/haulnet-server) | Server package for operators: LuxonServer with config, Docker image and status endpoint |
| [haulnet-servers](https://github.com/haulnet/haulnet-servers) | The public list of official and community servers, live at [servers.haulnet.cc](https://servers.haulnet.cc/) |

Website and documentation: [haulnet.cc](https://haulnet.cc/). Status: **pre-release**, tested by two players on two
PCs; the first packaged release is in preparation, until then the mod is built from source.

Security reports: [security@haulnet.cc](mailto:security@haulnet.cc). Other questions:
[contact@haulnet.cc](mailto:contact@haulnet.cc).

The server side is the unmodified [LuxonServer](https://github.com/niansa/LuxonServer), an open-source
Photon-compatible server. Haulnet needs no Photon account and no administrator rights, and it does not
support unlicensed copies of the game.

---

<sub>Haulnet is an independent fan project. It is not affiliated with or endorsed by semiwork (developers of
R.E.P.O.) or Exit Games GmbH. "R.E.P.O." and "Photon" are trademarks of their respective owners and are used
only to describe compatibility.</sub>
