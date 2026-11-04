# Ishtar

## English

Ishtar is a website for an artist-streamer, bringing together a creative portfolio, a personal introduction, and content about art, gaming, and community. The project is named after Ishtar, a Mesopotamian deity.

### What's included

- **Home page (`index.html`):** Hero section with a background image, navigation, and modals for contact, social media, friends, legal information, and cookie settings.
- **About page (`about.html`):** An introduction to the artist and streamer, with images that can be enlarged.
- **Portfolio (`gallery.html`):** A gallery for artwork, animations, and videos. Filters help visitors browse the collection, and media can be opened in a larger view.
- **English and German:** A language switcher on every page. The selected language is saved in the browser.
- **Responsive navigation:** A collapsible menu for smaller screens.
- **GitHub Pages:** The workflow at `.github/workflows/jekyll-gh-pages.yml` deploys the site when changes are pushed to the `main` branch. It can also be started manually.

### Project structure

```text
.
├── index.html                 # Home page
├── about.html                 # About page
├── gallery.html               # Portfolio and media gallery
├── assets/
│   ├── css/styles.css         # Layout, colors, and responsive styling
│   ├── js/main.js             # Interactions and English/German text
│   ├── fonts/                 # Locally hosted fonts
│   ├── gallery/               # Gallery images, animations, and videos
│   ├── img/                   # Background and about-page images
│   ├── logo/                  # Logo
│   └── svg/                   # Icons
└── .github/workflows/         # GitHub Pages deployment
```

### Run locally

No build step is required. You can open `index.html` directly in a browser. Alternatively, start a simple HTTP server for local preview, for example:

```sh
python -m http.server 8000
```

Then open the local address shown in the terminal, usually `http://localhost:8000`, in your browser.

### Customize the content

- **Text and translations:** English (`en`) and German (`de`) translations are in `assets/js/main.js`. Keep both language versions updated for text linked through `data-i18n`.
- **Portfolio:** Gallery items and their media paths are in `gallery.html`. Add media to `assets/gallery/` and reference it there with the appropriate gallery type, description, and credit.
- **Images:** About-page images are in `assets/img/`; the hero background is set in `assets/css/styles.css`.
- **Contact details and profiles:** Before publishing, replace example email addresses and generic profile links in the HTML files with your own details and profiles.
- **Legal information:** Review the placeholders in the legal modal and replace them with the required details before publishing.

## Deutsch

Ishtar ist eine Website für einen Artist-Streamer: Sie verbindet ein kreatives Portfolio mit einer persönlichen Vorstellung und einem Auftritt rund um Kunst, Gaming und Community. Der Projektname ist von Ishtar, einer mesopotamischen Gottheit, inspiriert.

### Was die Website enthält

- **Startseite (`index.html`):** Hero-Bereich mit Hintergrundbild, Navigation und Modals für Kontakt, soziale Medien, Freund*innen, rechtliche Informationen und Cookie-Einstellungen.
- **Über-Seite (`about.html`):** Vorstellung des Artists und Streamers sowie Bilder, die sich vergrößern lassen.
- **Portfolio (`gallery.html`):** Galerie für Artworks, Animationen und Videos. Die Filter helfen beim Durchstöbern; Medien können in einer Großansicht geöffnet werden.
- **Deutsch und Englisch:** Sprachumschalter auf allen Seiten. Die gewählte Sprache wird im Browser gespeichert.
- **Responsive Navigation:** Ein aufklappbares Menü für kleinere Bildschirme.
- **GitHub Pages:** Der Workflow unter `.github/workflows/jekyll-gh-pages.yml` veröffentlicht die Website nach Pushes auf den Branch `main`; ein manueller Start ist ebenfalls möglich.

### Projektstruktur

```text
.
├── index.html                 # Startseite
├── about.html                 # Über mich
├── gallery.html               # Portfolio und Mediengalerie
├── assets/
│   ├── css/styles.css         # Layout, Farben und responsive Gestaltung
│   ├── js/main.js             # Interaktionen und deutsche/englische Texte
│   ├── fonts/                 # Lokal eingebundene Schriftarten
│   ├── gallery/               # Galerie-Bilder, Animationen und Videos
│   ├── img/                   # Hintergrund- und About-Bilder
│   ├── logo/                  # Logo
│   └── svg/                   # Icons
└── .github/workflows/         # GitHub-Pages-Bereitstellung
```

### Lokal ansehen

Es ist kein Build-Schritt erforderlich. `index.html` lässt sich direkt im Browser öffnen. Für die lokale Vorschau kann alternativ ein einfacher HTTP-Server verwendet werden, zum Beispiel:

```sh
python -m http.server 8000
```

Danach die angezeigte lokale Adresse, üblicherweise `http://localhost:8000`, im Browser öffnen.

### Inhalte anpassen

- **Texte und Übersetzungen:** In `assets/js/main.js` liegen die deutschen (`de`) und englischen (`en`) Übersetzungen. Wenn ein Text über `data-i18n` eingebunden ist, sollten beide Sprachvarianten gepflegt werden.
- **Portfolio:** Galerie-Einträge und ihre Medienpfade stehen in `gallery.html`. Neue Medien in `assets/gallery/` ablegen und dort mit passendem Galerie-Typ, Beschreibung und Credit ergänzen.
- **Bilder:** Bilder der Über-Seite liegen in `assets/img/`; der Hero-Hintergrund wird in `assets/css/styles.css` festgelegt.
- **Kontaktdaten und Profile:** Vor der Veröffentlichung Beispieladressen und allgemeine Profil-Links in den HTML-Dateien durch die eigenen Kontaktdaten und Profile ersetzen.
- **Rechtliche Angaben:** Platzhalter im rechtlichen Dialog vor der Veröffentlichung prüfen und durch die erforderlichen Angaben ersetzen.
