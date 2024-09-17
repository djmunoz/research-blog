---
layout: post
title: "Installing and Running FARGO3D on Windows"
tags: ["Coding", "Research"]
published: true
date: 2024-09-17
author:  "Noah R. Gordon"
---

I generally do not encourage students to get a Windows machine for professional/research use. But the reality is that many undergraduates already own computers that run Windows, and it is thus more convenient to make do with what we have at hand. An example of this is when we want to run small hydrodynamical simulations on a Windows laptop, which coud already be equipped with powerful specs if it was designed for, say, gaming.

I have asked NAU undergraduate Noah Gordon to look into installing the state-of-the-art hydro code [FARGO3D](https://fargo3d.bitbucket.io/index.html#)

Intalling FARGO3D on Windows Powershell
=======================================

# Installing a package manager like Chocolatey

To compile FARGO3D we need `cmake`. We will install it using the package manager [Chocolatey](https://community.chocolatey.org/packages/cmake)

```console
foo@bar:~$ Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

```console
foo@bar:~$ whoami
foo
```

Lots of text.#

---

# Chapter 2

Some more text

---

