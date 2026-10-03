---
title: Understanding containers
description: "The ideas behind containers, explained from scratch. What they are, how they differ from virtual machines, the kinds you will meet, and where they came from."
---

# Understanding containers

Before you type another `docker` command, it is worth knowing what is actually happening when you do. This chapter has no commands to run. It is the story and the mental model, told plainly, so that every error message and every flag you meet later has a place to land.

Read these in order. Each one leans on the one before it.

# Concepts

* [Why containers exist: the evolution of software deployment](why-containers-exist.md) - Four eras of putting software on servers, the two headaches that never went away, and how containers finally cure them. The "why" before the "what".
* [What is a container?](what-is-a-container.md) - A program with its own private view of the computer. The whole idea in one page, including the Linux pieces that make it work.
* [Containers vs virtual machines](containers-vs-virtual-machines.md) - Two ways to put a program in a box, why one is heavier, and when you still want the heavy one.
* [Types of containers](types-of-containers.md) - Application, system, sandboxed, and Windows containers. Which one Docker is, and how to recognize the others.
* [The history and evolution of containers](history-and-evolution-of-containers.md) - From a 1979 Unix trick to Docker to Kubernetes, and why it took so long.
