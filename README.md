# Claude Code Plugin Marketplace

Plugin Marketplace by **SoftwareEngineering Hauschel** — [hauschel.de](https://hauschel.de)

## English

### What is a Claude Code Plugin Marketplace?

A Plugin Marketplace is a curated registry of [Claude Code Plugins](https://docs.anthropic.com/en/docs/claude-code/plugins). It allows users to discover and install plugins (such as MCP servers) directly from within Claude Code using the `/install` command — no manual configuration needed.

For details on how marketplaces work, see the [official Plugin documentation](https://docs.anthropic.com/en/docs/claude-code/plugins).

### Available Plugins

| Plugin | Description |
|--------|-------------|
| [jdt-mcp-server](https://github.com/hauschel-ai-tools/jdt-mcp-server) | MCP Server exposing Eclipse JDT features for Java development — code analysis, refactoring, type hierarchies, find references, and more. |

### Prerequisites

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) installed (v1.0.0+)
- For jdt-mcp-server: Java 21 or newer

### Installation

All commands below are run **inside Claude Code** (not in a regular terminal).

#### Step 1: Add this marketplace

```
/install hauschel-ai-tools/claude-code-marketplace
```

#### Step 2: Install a plugin

```
/install jdt-mcp-server
```

#### Step 3: Verify

```
/mcp
```

You should see `jdt-mcp-server` listed as a connected MCP server.

### Update

To update a plugin to the latest version:

```
/install jdt-mcp-server
```

### Uninstall

To remove a plugin:

```
/uninstall jdt-mcp-server
```

### License

This marketplace is licensed under the [Apache License 2.0](LICENSE). Individual plugins may have their own licenses — check the respective plugin repositories for details.

---

## Deutsch

### Was ist ein Claude Code Plugin Marketplace?

Ein Plugin Marketplace ist ein kuratiertes Verzeichnis von [Claude Code Plugins](https://docs.anthropic.com/en/docs/claude-code/plugins). Er ermoeglicht es, Plugins (z.B. MCP-Server) direkt in Claude Code mit dem `/install`-Befehl zu entdecken und zu installieren — ohne manuelle Konfiguration.

Details zur Funktionsweise findest du in der [offiziellen Plugin-Dokumentation](https://docs.anthropic.com/en/docs/claude-code/plugins).

### Verfuegbare Plugins

| Plugin | Beschreibung |
|--------|-------------|
| [jdt-mcp-server](https://github.com/hauschel-ai-tools/jdt-mcp-server) | MCP-Server fuer Eclipse JDT-Features in der Java-Entwicklung — Code-Analyse, Refactoring, Typ-Hierarchien, Referenzen finden und mehr. |

### Voraussetzungen

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) installiert (v1.0.0+)
- Fuer jdt-mcp-server: Java 21 oder neuer

### Installation

Alle Befehle werden **in Claude Code** ausgefuehrt (nicht im normalen Terminal).

#### Schritt 1: Diesen Marketplace hinzufuegen

```
/install hauschel-ai-tools/claude-code-marketplace
```

#### Schritt 2: Ein Plugin installieren

```
/install jdt-mcp-server
```

#### Schritt 3: Pruefen

```
/mcp
```

`jdt-mcp-server` sollte als verbundener MCP-Server angezeigt werden.

### Aktualisieren

Um ein Plugin auf die neueste Version zu aktualisieren:

```
/install jdt-mcp-server
```

### Deinstallieren

Um ein Plugin zu entfernen:

```
/uninstall jdt-mcp-server
```

### Lizenz

Dieser Marketplace steht unter der [Apache License 2.0](LICENSE). Einzelne Plugins koennen eigene Lizenzen haben — siehe die jeweiligen Plugin-Repositories fuer Details.

---

## Maintainer

SoftwareEngineering Hauschel — [hauschel.de](https://hauschel.de)
