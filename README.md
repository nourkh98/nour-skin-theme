# Nour Skin Theme

**Premium Shopify Theme für Nour Skin - Wo Schönheit auf Licht trifft**

## Design

- Dunkler Hintergrund: `#1a1816`
- Helle Schrift: `#f2efe9`
- Gold-Akzente: `#d4af37`
- Schriftarten: Playfair Display + Inter

## Installation

### Schritt 1: Mit Shopify verbinden

1. Gehe zu deinem **Shopify Admin**
2. **Online-Store → Themes**
3. Klicke auf **"Theme hinzufügen" → "Theme aus GitHub verbinden"**
4. Verbinde dein GitHub-Konto
5. Wähle dieses Repository aus

### Schritt 2: Navigation einrichten

Erstelle diese Menüs unter **Online-Store → Navigation**:

**Hauptmenü:**
- Startseite → /
- Shop → /collections/all
- Hautpflege → /collections/hautpflege
- Haarpflege → /collections/haarpflege
- Über uns → /pages/ueber-uns

**Footer-Menüs:**
- Footer-Shop: Alle Produkte, Hautpflege, Haarpflege
- Footer-Hilfe: Versand, Rückgabe, FAQ, Kontakt
- Footer-Rechtliches: Impressum, Datenschutz, AGB

### Schritt 3: Kollektionen erstellen

Unter **Produkte → Kollektionen**:

1. **Hautpflege** - Bedingung: Produkt-Typ = Hautpflege
2. **Haarpflege** - Bedingung: Produkt-Typ = Haarpflege
3. **Alle Produkte** - Bedingung: Preis > 0

### Schritt 4: Produkte hinzufügen

- Produkt-Typ: `Hautpflege` oder `Haarpflege`
- Tags: `bestseller`, `new`, `sale` (für Badges)

## Theme Struktur

```
├── assets/           # CSS und Assets
├── config/           # Theme-Einstellungen
├── layout/           # Haupt-Layout
├── locales/          # Übersetzungen
├── sections/         # Seiten-Sektionen
├── snippets/         # Wiederverwendbare Code-Teile
└── templates/        # Seiten-Templates
```

## Sektionen

- **Hero** - Startseite mit Slogan
- **Categories** - Kategorie-Karten (Hautpflege, Haarpflege, Körperpflege)
- **Products** - Produkt-Grid
- **About** - Über uns mit Features
- **Newsletter** - Newsletter-Anmeldung
- **Footer** - Footer mit Slogan

## Support

Bei Fragen: hello@nourskin.de
