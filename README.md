# ASP – Multiplayer Framework for Fighting Games in Godot

This project is part of my Advanced Specialised Project for the BSc Games Programming (SAE Institute, Cologne).

---

## Goal

The goal of this ASP is to design and implement a **scalable multiplayer framework** tailored for **1v1 fighting games**, using the **Godot 4.x Engine** and integrating **backend matchmaking and session management** through modern, open-source cloud technologies.

This framework should allow:
- **Real-time P2P or client-server multiplayer** over the internet
- **Matchmaking** (random)
- **Session hosting** (manual, cloud)
- **Replays** and **input delay buffering** (for rollback/netcode experiments)
- Optionally: integrate player authentication and basic persistent stats.

### Core Deliverables:
- A **playable prototype** of a fighting game (with 2 fighters)
- Fully functional **multiplayer framework**
- Backend services running via **Docker**
- Diagrams + technical documentation + weekly logs

---

##️ Technologies Used

### Game Engine & Frontend
- [Godot Engine 4.x](https://godotengine.org) (main development platform)
- GDScript (can be extended to C++ if needed)


### Backend Stack


### DevOps & Tools
- **Git + GitHub** – Version control
- **Miro / draw.io** – Diagrams and architecture
- **Markdown** – Weekly logs, notes, and documentation
- Optionally: **OBS** – To record weekly demo videos and progress

---

## Repository Structure

```bash
.
├── README.md                     # This file
├── .gitignore                    # Set for Godot
│
├── godot-project/                # The main Godot project
│   └── ...                  
│
├── backend/                      # Backend microservices
│   └── ...              
│
├── weekly-progress/             # Logs of weekly activity
│   ├── week1.md
│   ├── week2.md
│   └── ...
│
├── docs/                         # Technical documentation
│   ├── architecture.png
│   ├── api-design.md
│   └── research-notes.md
│
└── media/                        # Screenshots & video demos
    ├── screenshots/
    └── demo-videos/
