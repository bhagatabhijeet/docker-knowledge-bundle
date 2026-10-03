---
title: Bundle update log
description: "Chronological history of this knowledge bundle, newest first."
---

# Bundle Update Log

## 2026-10-03
* **Creation**: Added [Why containers exist: the evolution of software deployment](/understanding-containers/why-containers-exist.md) as the opening concept of the [Understanding containers](/understanding-containers/index.md) chapter. It walks through the four deployment eras (dedicated servers, virtual machines, the cloud, containers), the five-step ship pipeline, the two headaches of dedicated servers (wasted hardware and "works on my machine"), how VMs fixed them and what they cost (weight, boot time, configuration drift), and how containers fix that in turn.
* **Creation**: Added two illustrations under [assets/images/understanding-containers/](/assets/images/understanding-containers/): deployment-eras.svg and works-on-my-machine.svg, drawn in the book's palette.
* **Update**: Renumbered the chapter list in the README and the chapter index, pointed the README's "Ready?" link at the new opening page, and added three sources to [references](/references/index.md).

## 2026-10-01
* **Update**: Changed the repository license from the Unlicense to [Creative Commons Attribution 4.0 International](/LICENSE) and updated the README license section.
* **Creation**: Added the [Understanding containers](/understanding-containers/index.md) chapter with four concepts: [What is a container?](/understanding-containers/what-is-a-container.md), [Containers vs virtual machines](/understanding-containers/containers-vs-virtual-machines.md), [Types of containers](/understanding-containers/types-of-containers.md), and [The history and evolution of containers](/understanding-containers/history-and-evolution-of-containers.md), with four diagrams under [assets/images/understanding-containers/](/assets/images/understanding-containers/).
* **Creation**: Added the [Getting started](/getting-started/index.md) chapter with five concepts: [Installing Docker on Windows](/getting-started/installing-docker-on-windows.md), [Docker Desktop vs Docker Engine](/getting-started/docker-desktop-vs-docker-engine.md), [Installing Docker on WSL](/getting-started/installing-docker-on-wsl.md), [Installing Docker on Ubuntu](/getting-started/installing-docker-on-ubuntu.md), and [Installing Docker on Mac](/getting-started/installing-docker-on-mac.md).
* **Creation**: Added illustrated screenshots under [assets/images/getting-started/](/assets/images/getting-started/). The WSL integration page uses a real Docker Desktop v4.93.0 screenshot (wsl-integration-settings.png); the rest are hand-drawn illustrations in the book's palette, and each is captioned as such.
* **Creation**: Added the [references](/references/index.md) directory listing the official Docker and Microsoft pages the chapter was checked against.
* **Initialization**: Scaffolded the bundle to OKF v0.2 with a root [index.md](/index.md) and this log.
