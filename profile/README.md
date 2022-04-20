# **DockServer**

<p align="center">
    <a href="https://dockserver.io">
      <img src="https://raw.githubusercontent.com/dockserver/dockserver/master/wiki/docs/img/dockservee_animated.gif" alt="Join DockServer community">
    </a>
</p>

----- 

<p align="center">
    </br>
    <a href="https://discord.gg/FYSvu83caM">
        <img src="https://discord.com/api/guilds/830478558995415100/widget.png?label=Discord%20Server&logo=discord" alt="Join DockServer on Discord">
    </a>
    </br>
    <img src="https://img.shields.io/liberapay/receives/dockserver.svg?logo=liberapay">
    </br>
    <a href="https://github.com/dockserver/dockserver/releases/latest">
        <img src="https://img.shields.io/github/v/release/dockserver/dockserver?include_prereleases&label=Latest%20Release&logo=github" alt="Latest Official Release on GitHub">
    </a>
    </br>
    <a href="https://github.com/dockserver/dockserver/blob/master/LICENSE">
        <img src="https://img.shields.io/github/license/dockserver/dockserver?label=License&logo=mit" alt="MIT License">
    </a>
    </br>
    <noscript>
      <a href="https://liberapay.com/dockserver/donate">
      <img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a>
    </noscript>
</p>


_Docker + Traefik with Authelia and Cloudflare Protection_


---

Some stats of [DOCKSERVER](https://dockserver.io)![metrics](https://raw.githubusercontent.com/dockserver/dockserver/master/github-metrics.svg)


--- 


## Minimum Specs and Requirements

- Stable: Ubuntu 18/20/21 or Debian 9/10/11

- CPU 2 Cores or 2 VCores
- 4GB Ram
- 20GB Disk Space

- A VPS/VM or Dedicated Server
- your Domain or buy a new [namecheap](https://www.namecheap.com/)
- [Cloudflare](https://dash.cloudflare.com/sign-up) account free tier

---


## For Testing

- [Hetzner Cloud](https://www.hetzner.com/de/cloud)
- [Digital Ocean](https://www.digitalocean.com/)
- [Vault](https://www.vultr.com/)


---


## Pre-Install

1. Login to your Cloudflare Account & goto DNS click on Add record.
1. Add 1 **A-Record** pointed to your server's ip.
1. Copy your [CloudFlare-Global-Key](https://support.cloudflare.com/hc/en-us/articles/200167836-Managing-API-Tokens-and-Keys) and [CloudFlare-Zone-ID](https://support.cloudflare.com/hc/en-us/articles/200167836-Managing-API-Tokens-and-Keys).


---


## Set the following on Cloudflare

1. `SSL = FULL` **( not FULL/STRICT )**
1. `Always on = YES`
1. `HTTP to HTTPS = YES`
1. `RocketLoader and Broli / Onion Routing = NO`
1. `TLS min = 1.2`
1. `TLS = v1.3`


---


### Easy Mode install

Run the following command:

```sh
sudo wget -qO- https://git.io/J3GDc | sudo bash
```

<details>
  <summary>Long commmand if the short one doesn't work.</summary>
  <br />

```sh
sudo wget -qO- https://raw.githubusercontent.com/dockserver/dockserver/master/wgetfile.sh | sudo bash
```

</details>


---

<!--START_SECTION:activity-->

1. ❌ Closed PR [#456](https://github.com/dockserver/dockserver/pull/456) in [dockserver/dockserver](https://github.com/dockserver/dockserver)
<!--END_SECTION:activity-->


---

## Support

Kindly report any issues/broken-parts/bugs on [github](https://github.com/dockserver/dockserver/issues) or [discord](https://discord.gg/A7h7bKBCVa)

<noscript><a href="https://liberapay.com/dockserver/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>

---

## Code and Permissions

```sh
Copyright 2021 @dockserver
Code owner @dockserver
Dev Code @dockserver
Co-Dev -APPS- @CONTRIBUTORS-LIST
```

---
