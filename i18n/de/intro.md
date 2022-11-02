---
sidebar_position: 1
---

# Tutorial-Einführung

Entdecken wir **Docusaurus in weniger als 5 Minuten**.

## Einstieg

Beginnen Sie mit der **Erstellung einer neuen Website**.

Oder **testen Sie Docusaurus sofort** mit **[docusaurus.new](https://docusaurus.new)**.

### Was Sie brauchen

- [Node.js](https://nodejs.org/en/download/) Version 16.14 oder höher:
  - Bei der Installation von Node.js wird empfohlen, alle Kontrollkästchen in Bezug auf Abhängigkeiten zu aktivieren.

## Eine neue Website generieren

Erstellen Sie eine neue Docusaurus-Website mit der **classic Vorlage**.

Die classic Vorlage wird automatisch zu Ihrem Projekt hinzugefügt, nachdem Sie den Befehl ausgeführt haben:

```bash
npm init docusaurus@latest my-website classic
```

Sie können diesen Befehl in der Eingabeaufforderung, der Powershell, dem Terminal oder einem anderen integrierten Terminal Ihres Code-Editors eingeben.

Der Befehl installiert auch alle notwendigen Abhängigkeiten, die Sie zum Ausführen von Docusaurus benötigen.

## Starten Sie Ihre Website

Starten Sie den Entwicklungsserver:

```bash
cd my-website
npm run start
```

Der Befehl `cd` wechselt das Verzeichnis, in dem Sie gerade arbeiten. Um mit Ihrer neu erstellten Docusaurus-Website zu arbeiten, müssen Sie im Terminal dorthin navigieren.

Der Befehl `npm run start` erstellt Ihre Website lokal und stellt sie über einen Entwicklungsserver bereit, so dass Sie sie unter http://localhost:3000/ ansehen können.

Öffnen Sie `docs/intro.md` (diese Seite) und bearbeiten Sie einige Zeilen: die Website **lädt automatisch** neu und zeigt Ihre Änderungen an.
