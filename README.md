# Space Battle — Multiplayer 2D Game (Thesis Project)

**Author:** Kaloyan Kalaydzhiev
**University:** University of Piraeus, Department of Informatics  
**Supervisor:** Prof. E. Alepis  
**Date:** September 2025  

---

## Overview
This project presents the design and implementation of **Space Battle**, a 2D multiplayer shooter built with Unity.  
It targets Android as the primary platform, with optional Windows PC cross-play.

The focus was on:
- **Host-authoritative networking** using Unity Lobby, Relay, and Netcode for GameObjects (NGO)
- **Mobile-first design** — responsive on-screen controls for portrait and landscape modes
- **Lightweight local persistence** via JSON

---

## Key Features
- Real-time 1v1 or 2v2 matches (host-authoritative)
- Three distinct weapons (bullets, rocket, electric beam)
- Time-based power-ups and temporary modifiers
- Built-in layout editor for touch controls
- Cross-platform compatibility (Android ↔ Windows)

---

## Architecture Summary
- **Engine:** Unity (6000.0.29f1)
- **Networking:** Unity Lobby / Relay + NGO (v2.5)
- **Transport:** Unity Transport Protocol (UDP)

---

## Code Availability
The source code is kept private due to planned future development.  
Documentation and design details are open for review.

