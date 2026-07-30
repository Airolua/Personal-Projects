# Roblox Studio Projects

Personal creations I've made in the past that I believe to reasonably reflect my coding ability and provide insight into my approach to architecture, problem-solving, and code quality. Each project here was built (or rebuilt) with production-safe patterns in mind — clear client/server boundaries, modular structure, and an eye toward maintainability rather than just "getting it working."

I'm currently open for commission work — see [Contact](#contact) below.

---

## Tech Stack

- **Language:** Luau
- **Tooling:** [Rojo](https://rojo.space/) (filesystem → Studio sync), [Wally](https://wally.run/) (package management)
- **Editor:** VS Code
- **Architecture patterns:** ModuleScripts, RemoteEvents/RemoteFunctions, server-authoritative game state

---

## Projects

| Project | Description | Highlights | Status |
|---|---|---|---|
| [`project-name/`](./project-name) | One-line description of what it does | e.g. server/client architecture, custom EQ system, procedural generation | 🚧 In Progress |
| [`project-name-2/`](./project-name-2) | One-line description of what it does | e.g. RemoteEvent-based combat system | ✅ Complete |
| [`project-name-3/`](./project-name-3) | One-line description of what it does | e.g. inventory system with DataStore persistence | ✅ Complete |

> **Start here:** if you only look at one project, check out `[project-name]/` — it's the clearest example of my client/server architecture and code organization.

---

## Project Structure

Most projects in this repo follow a similar layout:

```
project-name/
├── src/
│   ├── client/       # LocalScripts, client-side controllers
│   ├── server/       # Server-side logic, ModuleScripts
│   └── shared/        # Shared modules (ReplicatedStorage)
├── wally.toml         # Package dependencies
├── default.project.json  # Rojo project file
└── README.md           # Project-specific notes
```

---

## Running These Projects Locally

1. Clone the repo
2. Install [Rojo](https://rojo.space/docs/installation/) and [Wally](https://github.com/UpliftGames/wally#installation)
3. From a project's directory, run `wally install` to pull dependencies
4. Run `rojo serve` and connect via the Rojo Studio plugin

---

## Contact

Available for commission-based Roblox development work.

- **Discord:** placeholder
- **Email:** placeholder
- **Portfolio/Website:** placeholder

---

## License

Placeholder — decide per-project (MIT is a common default for portfolio code).
