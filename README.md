# Willkommen bei LazyMC v2

## Projektübersicht

LazyMC v2 ist die vollständige Neuentwicklung des ursprünglichen LazyMC-Servers.

Dabei werden bestehende Systeme nicht einfach übernommen, sondern technisch neu entwickelt, optimiert und erweitert. Ziel ist eine moderne, wartbare und langfristig erweiterbare Codebasis.

Diese GitHub-Organisation dient ausschließlich der Entwicklung aller Komponenten von LazyMC v2.

---

# Projektziele

- Saubere und modulare Architektur
- Eigene Plugins statt Standardlösungen
- Hohe Performance
- Wartbarer und dokumentierter Code
- Klare Trennung zwischen API, Core und Modulen
- Skalierbare Infrastruktur
- Langfristige Weiterentwicklung

---

# Entwicklungsphilosophie

Bei LazyMC steht Qualität vor Geschwindigkeit.

Neue Features werden erst implementiert, wenn sie den Qualitätsstandards entsprechen. Kurzfristige Lösungen oder schlecht wartbarer Code werden grundsätzlich vermieden.

Wir entwickeln Systeme, die auch in mehreren Jahren noch problemlos erweitert werden können.

---

# Technologie

Je nach Repository kommen unter anderem folgende Technologien zum Einsatz:

- Java 21
- PaperMC
- Gradle
- MongoDB
- MariaDB / MySQL
- Redis
- Docker
- GitHub Actions
- IntelliJ IDEA

---

# Projektstruktur

```text
Core
├── API
├── Common
├── Database
├── Network
├── Authentication
├── Permissions
├── Economy
├── Clans
├── PvP
├── Minigames
├── Utilities
└── Shared
```

Weitere Module werden im Laufe der Entwicklung ergänzt.

---

# Entwicklungsrichtlinien

Vor jedem Commit sollte sichergestellt werden, dass:

- der Code kompiliert,
- keine Compiler-Warnungen entstehen,
- keine Debug-Ausgaben enthalten sind,
- bestehende Funktionen nicht beeinträchtigt werden,
- der Code den Projektstandards entspricht.

Pull Requests sollten klar beschrieben und möglichst klein gehalten werden.

---

# Branch-Konzept

```text
main
│
├── develop
│
├── feature/*
├── bugfix/*
├── hotfix/*
└── release/*
```

Direkte Commits auf `main` sind nicht vorgesehen.

---

# Dokumentation

Jedes Repository sollte mindestens folgende Dateien enthalten:

- README.md
- LICENSE (falls öffentlich)
- CONTRIBUTING.md
- CODE_OF_CONDUCT.md (optional)
- CHANGELOG.md

---

# Ziel

LazyMC v2 soll kein gewöhnlicher Minecraft-Server werden.

Unser Ziel ist eine moderne Serverplattform mit einer hochwertigen Architektur, eigener Technologie und langfristiger Wartbarkeit.
