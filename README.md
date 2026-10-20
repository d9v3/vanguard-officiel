# Vanguard — published versions

This repository only holds the published programs of Vanguard (security check and repair kit for PCs and home
networks), so that Vanguard can update itself without its USB key. The source code lives elsewhere.

Each release has the three programs (`vanguard-windows-x86_64.exe`, `vanguard-linux-x86_64`, `vanguard-macos`), their
SHA-256 fingerprints, and `derniere.txt`: the version, then the fingerprint and size of each program, signed with
Ed25519 (`derniere.txt.sig`) on the author's computer. Vanguard only installs a program described by a manifest that
the author's key signed, and only a newer version: a change made here by anyone else is refused.

---

Ce dépôt ne contient que les programmes publiés de Vanguard, pour qu'il se mette à jour sans sa clé USB. Chaque
version a les trois programmes, leurs empreintes SHA-256 et `derniere.txt`, signé en Ed25519 sur l'ordinateur de
l'auteur : Vanguard n'installe qu'un programme décrit par un manifeste que cette clé a signé, et jamais une version
plus ancienne.
