# NEON//JAVA

Cyberpunk RPG-style mobile app for learning Java, built with Java 21, Maven and Codename One.

## Development status

- **Baseline:** v0.7 development baseline — not yet a stable release.
- **Runtime:** Java 21 (Temurin), Maven Wrapper, Codename One.
- **Game structure:** Profile, Quests, Map, Equipment.
- **Character creation:** nickname, appearance/avatar and archetypes (Netrunner, Techie, Solo).
- **Learning content:** prepared offline Java tasks with deliberate “gotcha” cases.
- **Combat:** timed quiz encounters, player/enemy HP, ATK/DEF and XP/credit rewards are planned/in progress.
- **AI assistant:** intentionally out of scope for the current phase.

## Build

Use JDK 21 (Temurin recommended), project language level 17.

```powershell
.\run.bat
```

## Important verification note

The project is a development baseline. The full Maven simulator build for v0.7 has not yet been confirmed. Earlier simulator runs exposed runtime layout and responsive UI issues; do not treat this baseline as a stable release.

## Product direction

See:
- `docs/PROJECT_STATUS_RU.md`
- `docs/ROADMAP_RU.md`
- `docs/GITHUB_AND_JIRA_BACKLOG_RU.md`

## Repository hygiene

Do not commit IDE metadata, local logs, build output, API keys, `.env` files, personal data, or machine-specific paths.
