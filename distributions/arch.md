---
marp: true
title: Arch Linux
theme: default
author: Zachary Tucker
---

# Arch Linux
Keep It Simple, Stupid 

--- 

# History

- Judd Vinet began work on Arch in early 2001.
- First release was on March 11th, 2002.
- ArchWiki was created on July 8th, 2005.
- Late 2007 Aaron Griffin becomes lead developer.
- Between 2012 & 2013 System V was replaced by systemd

---

# Guiding Principles

---

## Simplicity
- Arch Linux defines simplicity as *without unnecessary additions or modifications*
- Software is released by the upstream developers with minimal downstream changes.
- Does not provide automation features for things like enabling a service.
- GUI configuration tools are not officially provided encouraging users to perform most system configuration from the shell and a text editor.
- No default desktop environment

---

## Modernity
- Strives to maintain the latest stable release of its software as long as systemic package breakage can be reasonably avoided.
  - Up to the user to ensure packages will not break things
- [Rolling release](https://en.wikipedia.org/wiki/Rolling_release) allows for one time installation with continuous upgrades.

---

## Pragmatism
- Arch linux is a pragmatic distribution rather than an ideological one. 
- Principles are used as useful guidelines
- Free and open source software for people who prefer it, as well as proprietary software packages for people who care more about functionality than ideology. 

---

## User centrality
- Arch Linux has always been, and always will be, *user centric* rather than *user friendly*.
- Fills the needs of those contributing to it, rather than trying to appeal to as many users as possible.
- "Targeted at the proficient GNU/Linux user, or anyone with a do-it-yourself attitude who is willing to read the documentation, and solve their own problems"
- Very active community that highly values community contributions.
- [ArchWiki](https://wiki.archlinux.org/title/Main_page)

---

## Versatility
Arch Linux is a general-purpose distribution. Upon installation, **only a command-line environment is provided**; rather than tearing out unneeded and unwanted packages, the user is offered the **ability to build a custom system** by choosing among thousands of high-quality packages provided in the official repositories for the x86-64 architecture
\
\- Arch Wiki

---

# pacman
- One of the major distinguishing features of Arch Linux.
- Goal is to make it possible to easily manage packages, whether they are from the official repositories or the user's own builds.
- Written in C and uses the bsdtar(1) tar format for packaging
- [pacman page](https://wiki.archlinux.org/title/pacman)

---

## AUR - Arch User Repository
- Community-driven repository for Arch users
- Created to organize and share new packages from the community and to help expedite popular packages' inclusion into the community repository
- A good number of new packages that enter the official repositories start in the AUR.
\
[AUR Wiki Page](https://wiki.archlinux.org/title/Arch_User_Repository)