<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="haulnet-logo-on-dark.svg">
    <img src="haulnet-logo-on-light.svg" alt="Haulnet" height="64">
  </picture>
</p>

<p align="center"><b>Play R.E.P.O. with friends on a server you control.</b></p>

R.E.P.O. sends every game through Photon Cloud, even when the players sit on the same network. Haulnet is a
mod that brings direct play back: the host's game runs the server, and friends connect over the same LAN,
any VPN they already use, IPv6 or a forwarded port. When a direct path is not possible, the game can live on
a community server instead. Out of the box nothing changes: Photon Cloud stays one click away.

| Repository | What it is |
|---|---|
| [haulnet-repo](https://github.com/haulnet/haulnet-repo) | The mod (BepInEx 5): host on your PC, join by invite or address, pick a community server |
| [haulnet-server](https://github.com/haulnet/haulnet-server) | Server package for operators: LuxonServer with config, Docker image and status endpoint |
| [haulnet-servers](https://github.com/haulnet/haulnet-servers) | The public list of community servers, published at [servers.haulnet.cc](https://servers.haulnet.cc/) |

Website: [haulnet.cc](https://haulnet.cc/). Status: **pre-alpha**. The first release is in preparation; until then
the mod is built from source.

Security reports: [security@haulnet.cc](mailto:security@haulnet.cc). Other questions:
[contact@haulnet.cc](mailto:contact@haulnet.cc).

The server side is the unmodified [LuxonServer](https://github.com/niansa/LuxonServer), an open-source
Photon-compatible server. Haulnet needs no Photon account and no administrator rights, and it does not
support unlicensed copies of the game.

---

<sub>Haulnet is an independent fan project. It is not affiliated with or endorsed by semiwork (developers of
R.E.P.O.) or Exit Games GmbH. "R.E.P.O." and "Photon" are trademarks of their respective owners and are used
only to describe compatibility.</sub>
