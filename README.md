# Abwasser Stegesiedlung

Informationsseite für Anwohnerinnen und Anwohner der Stegesiedlung Schönholz zum Thema Abwasserbeseitigung.

Veröffentlicht unter: https://thimble9633.github.io/abwasser-stegesiedlung

## Lokale Entwicklung

**Voraussetzung:** Ruby ≥ 3.0 (macOS-Systemruby ist zu alt – Installation via Homebrew empfohlen)

```zsh
# Einmalig: Ruby installieren und Pfad setzen
brew install ruby
echo 'export PATH="/opt/homebrew/opt/ruby/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc

# Einmalig: Abhängigkeiten installieren
bundle install
```

Server starten:

```zsh
bundle exec jekyll serve
```

Die Seite ist dann unter **http://localhost:4000/abwasser-stegesiedlung/** erreichbar.
Jekyll erkennt Dateiänderungen automatisch – Browser-Reload genügt.

Optional mit automatischem Browser-Reload:

```zsh
bundle exec jekyll serve --livereload
```

## Neue Meldung veröffentlichen

Datei in `_posts/` anlegen nach dem Schema `YYYY-MM-DD-titel.md`:

```yaml
---
layout: post
title: "Titel der Meldung"
date: 2026-09-23
---

Inhalt hier...
```
