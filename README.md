# Docker, One Step at a Time

### The free, friendly book that makes Docker finally click

<p align="center">
	<img src="assets/images/docker-book-cover.svg" alt="Colorful illustrated cover for Docker, a free and friendly field guide to containers, images, and building at your own pace." width="100%">
</p>

<p align="center">
	<strong>No jargon left unexplained. No step skipped. No account, course, or credit card required.</strong><br>
	Just plain Markdown, friendly pictures, and the feeling of things making sense.
</p>

---

## Have you ever...

* Pasted `docker run` from a tutorial, watched it work, and had **no idea why**?
* Nodded along when someone said "it's basically a lightweight VM," while quietly suspecting that is not quite right? *(It isn't.)*
* Installed Docker Desktop, seen a whale in your taskbar, and wondered what it is actually **doing** in there?
* Heard "image," "container," "namespace," "cgroup," "WSL 2," "Engine," and felt your eyes slide off the page?

Then you are exactly who this book is for. Every one of those is answered here, in order, in plain words, with a picture.

## What you will be able to do

By the end of the first two chapters you will:

| | |
|---|---|
| **See through the magic** | Explain in one sentence what a container really is, and why that is not what most people think. |
| **Win the VM argument** | Know precisely how a container differs from a virtual machine, and when you still want the VM. |
| **Have Docker running** | On Windows, inside WSL, on Ubuntu, or on a Mac, with every command checked against the official docs this month. |
| **Read any error message** | Because you will know which piece, client, daemon, image, or kernel, is talking. |
| **Tell the story** | From one-app-per-server through virtual machines and the cloud to containers, and from a 1979 Unix command to Kubernetes. Why each step happened, and why Docker took off when earlier tools did not. |

## Taste it in sixty seconds

Already have Docker installed? Open a terminal and type this:

```bash
docker run hello-world
```

A few lines scroll by and end with **Hello from Docker!** In those few seconds your computer downloaded a frozen snapshot of a tiny program, built a private little world for it with its own files and its own view of the machine, ran it, and threw the world away.

Not installed yet? That is chapter two, and it takes about ten minutes. Curious what just happened? That is chapter one.

<p align="center">
	<img src="assets/images/understanding-containers/container-anatomy.svg" alt="Diagram: a container is a normal process wearing blinders (namespaces) and a seatbelt (cgroups), sharing one Linux kernel with its neighbors." width="100%">
</p>

## The book so far

### Chapter 1 · [Understanding containers](understanding-containers/)

*The ideas, with zero commands to run.*

1. [Why containers exist](understanding-containers/why-containers-exist.md) — Four eras of shipping software, two headaches that never went away, and the fix that finally stuck. Read this and "works on my machine" never puzzles you again.
2. [What is a container?](understanding-containers/what-is-a-container.md) — A program with blinders and a seatbelt. The whole trick, and the three Linux words you need to see it.
3. [Containers vs virtual machines](understanding-containers/containers-vs-virtual-machines.md) — One fakes a computer. The other fakes a view. Why it matters, and how your laptop secretly uses both.
4. [Types of containers](understanding-containers/types-of-containers.md) — Docker is one of four families. Meet the cousins so they never confuse you again.
5. [The history and evolution of containers](understanding-containers/history-and-evolution-of-containers.md) — Forty years in the making, two years to take over. The best part is why.

### Chapter 2 · [Getting started](getting-started/)

*Hands on the keyboard. Pick your operating system.*

| Your machine | Your page | What you get |
|---|---|---|
| Windows 10 or 11 | [Installing Docker on Windows](getting-started/installing-docker-on-windows.md) | Docker Desktop on WSL 2, three install routes, first run |
| Windows, but you live in a Linux terminal | [Installing Docker on WSL](getting-started/installing-docker-on-wsl.md) | `docker` inside Ubuntu-on-Windows, with Desktop or without it |
| Ubuntu | [Installing Docker on Ubuntu](getting-started/installing-docker-on-ubuntu.md) | Docker Engine straight on the kernel, no VM, no GUI |
| Mac, Apple silicon or Intel | [Installing Docker on Mac](getting-started/installing-docker-on-mac.md) | Drag-and-drop, Homebrew, or command line |
| Not sure what you just installed | [Docker Desktop vs Docker Engine](getting-started/docker-desktop-vs-docker-engine.md) | The one distinction that trips up almost everyone |

### Coming next

Your first real container. Images and where they come from. Writing a Dockerfile without copying one. Volumes, networks, and Compose. Each chapter lands in the [update log](log.md) when it is ready.

## Why this book reads differently

**Every term is explained the first time you meet it.** Kernel, process, namespace, cgroup, chroot, image layer. If a word would make a smart newcomer pause, there is a sentence right there that un-pauses them.

**Every idea gets an analogy and a picture.** The kernel is a building superintendent. A namespace is a set of blinders. A VM fakes a whole computer; a container fakes one program's privacy. Each page has an illustration drawn in the same warm palette as the cover.

**Every command is checked.** Install steps are verified against the current official Docker and Microsoft documentation and cite them with footnotes. Each page carries a `stale_after` date so you can see how fresh it is.

**Every page ends with one sentence to keep.** Read nothing else and you still leave with the idea.

**Short pages, strict order.** Each page leans only on the pages before it. You never need to know something you have not been told yet.

## How to read it

* **In a browser, right here.** Start at [index.md](index.md). GitHub renders everything, pictures included.
* **In your editor.** Clone the repository and open the folder. It is plain Markdown and SVG. Nothing to install, nothing to build.
* **With a tool.** This repository follows the [Open Knowledge Format (OKF) v0.2](https://github.com/GoogleCloudPlatform/knowledge-catalog/blob/main/okf/SPEC.md): every page has machine-readable frontmatter with a type, tags, sources, and freshness dates. Point an agent or a search tool at it and it just works.

## Is this for me?

**I have never used a terminal.** Yes. Chapter 1 has no commands at all, and chapter 2 tells you exactly which window to open and what to type.

**I already use Docker every day but could not explain it.** Yes. Read chapter 1 in an afternoon and you will.

**I am on Windows.** Especially yes. Windows is where Docker is most confusing, and two of the five install pages are about getting it right there.

**I want Kubernetes.** Start here anyway. Kubernetes is containers at scale, and this is the shortest path to really understanding containers.

## Contribute

Found a typo, a stale command, or a sentence that made you pause? Open an issue or a pull request. The bar for every page is the same: the easiest, friendliest explanation of that idea anyone has written. If you can make a page clearer, you are welcome here.

## License

This book is licensed under the [Creative Commons Attribution 4.0 International License](LICENSE) (CC BY 4.0). Copy it, remix it, translate it, teach from it, print it for your class, even sell it, as long as you credit **Docker, One Step at a Time** and link back to this repository. The full legal text is in [LICENSE](LICENSE); the human-readable summary is at [creativecommons.org/licenses/by/4.0](https://creativecommons.org/licenses/by/4.0/).

Docker and the Docker whale are trademarks of Docker, Inc. This is an independent, unofficial learning resource.

---

<p align="center">
	<strong>Ready?</strong> Begin with <a href="understanding-containers/why-containers-exist.md">Why containers exist</a>. It takes ten minutes, and every Docker feature you meet afterwards will have a reason.
</p>
