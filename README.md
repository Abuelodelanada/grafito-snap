# grafito-snap

Snap package for [Grafito](https://github.com/ralsina/grafito), a simple, self-contained web-based log viewer for `journalctl`.

## 📦 What is this?

This repository contains the Snap packaging definition (`snapcraft.yaml`) for building and distributing Grafito as a Snap package for Ubuntu and other Linux distributions that support Snap.

## 🚀 Install

Once published to the Snap Store:

```bash
sudo snap install grafito
```

Or install manually from a local .snap file:

```bash
sudo snap install --dangerous grafito_*.snap
```


## 🛠️ Usage

Start the Grafito web UI as a daemon:

```bash
sudo snap start grafito.daemon
```


Or run manually in the terminal:


```bash
grafito
```


Then open http://localhost:3000 in your browser.


## 🐞 Bugs & Contributions

This repo only maintains the Snap packaging. For issues related to Grafito itself, please refer to the [upstream project](https://github.com/ralsina/grafito).