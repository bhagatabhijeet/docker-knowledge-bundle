---
title: References
description: "Official pages this bundle was checked against, grouped by chapter."
---

# References

Every concept in this bundle cites its sources in frontmatter and footnotes. This page gathers them in one place so you can go straight to the primary material.

# Getting started

* [Install Docker Desktop on Windows](https://docs.docker.com/desktop/setup/install/windows-install/) - System requirements, installer flags, per-user vs all-users mode.
* [Docker Desktop WSL 2 backend](https://docs.docker.com/desktop/features/wsl/) - Enabling the WSL 2 engine and per-distro integration.
* [Install WSL (Microsoft Learn)](https://learn.microsoft.com/en-us/windows/wsl/install) - The wsl --install command and version management.
* [Install Docker Engine on Ubuntu](https://docs.docker.com/engine/install/ubuntu/) - The apt repository method, convenience script, supported releases.
* [Linux post-installation steps](https://docs.docker.com/engine/install/linux-postinstall/) - The docker group and starting on boot.
* [Install Docker Desktop on Ubuntu](https://docs.docker.com/desktop/setup/install/linux/ubuntu/) - The .deb install and how Desktop coexists with Engine.
* [Install Docker Desktop on Mac](https://docs.docker.com/desktop/setup/install/mac-install/) - The .dmg, the command-line installer, Rosetta.
* [Homebrew cask docker-desktop](https://formulae.brew.sh/cask/docker-desktop) - The Homebrew route, renamed from the old docker cask.
* [Docker Engine overview](https://docs.docker.com/engine/install/) - Engine vs Desktop, licensing, release channels.

# Understanding containers

* [What is a container? (Docker concepts)](https://docs.docker.com/get-started/docker-concepts/the-basics/what-is-a-container/) - Docker's plain-language definition, used for the deployment-evolution page.
* [What is a virtual machine? (VMware)](https://www.vmware.com/topics/virtual-machine) - The vendor that defined the virtualization era, on what a VM is.
* [The NIST Definition of Cloud Computing, SP 800-145](https://csrc.nist.gov/pubs/sp/800/145/final) - The standard definition of on-demand, elastic cloud resources.
* [namespaces(7)](https://man7.org/linux/man-pages/man7/namespaces.7.html) and [cgroups(7)](https://man7.org/linux/man-pages/man7/cgroups.7.html) - The two kernel features every Linux container is built from.
* [chroot(2)](https://man7.org/linux/man-pages/man2/chroot.2.html) - The 1979 ancestor of the mount namespace.
* [FreeBSD Handbook, Jails](https://docs.freebsd.org/en/books/handbook/jails/) - The first complete system container, from 2000.
* [LXC introduction](https://linuxcontainers.org/lxc/introduction/) - The pre-Docker Linux container tool, still maintained.
* [Open Container Initiative](https://opencontainers.org/about/overview/) - The image and runtime standards that made container tools interchangeable.
* [gVisor](https://gvisor.dev/docs/) and [Kata Containers](https://katacontainers.io/) - Sandboxed and VM-backed container runtimes.
* [Windows and containers](https://learn.microsoft.com/en-us/virtualization/windowscontainers/about/) - Microsoft's overview of Windows containers and their two isolation modes.
* [Kubernetes overview](https://kubernetes.io/docs/concepts/overview/) - Orchestration, the layer above containers.
* [What is Docker?](https://docs.docker.com/get-started/docker-overview/) - Docker's own overview of images, layers, and the engine.
