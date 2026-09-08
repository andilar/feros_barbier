# Fero's Barbier Website

Eine einseitige, scrollbare Business-Website für Fero's Barbier in Braunschweig, plus
Impressum und Datenschutzerklärung als eigene Unterseiten.

## Struktur
```
feros_barbier/
├── index.html          ← die Haupt-Seite
├── impressum.html       ← Pflichtangaben gemäß § 5 DDG
├── datenschutz.html     ← Datenschutzerklärung gemäß DSGVO/TDDDG
├── robots.txt
├── sitemap.xml
├── assets/
│   ├── styles.css
│   ├── script.js
│   ├── site.webmanifest
│   ├── icons/            ← Favicon in mehreren Größen
│   └── images/            ← Logo & Fotos vom Laden (als .webp, Originale als Backup)
└── README.md
```

## Was beinhaltet diese Seite
- **Impressum & Datenschutz**: eigene Unterseiten, im Footer jeder Seite verlinkt
- **Favicon**: aus dem Logo erzeugt, in allen gängigen Größen (Browser-Tab, Homescreen)
- **Open-Graph-Tags**: für eine ansprechende Vorschau beim Teilen des Links auf
  WhatsApp/Facebook
- **Strukturierte Daten** (schema.org `HairSalon`): hilft Google, Adresse, Telefonnummer
  und Öffnungszeiten direkt in der Suche und auf Google Maps anzuzeigen
- **Bilder als WebP**: kleinere Dateigrößen, Lazy Loading für Bilder unterhalb des
  ersten Bildschirms
- **Barrierefreiheit**: Skip-Link für Tastatur-Nutzer, sichtbare Fokus-Umrandung bei
  Tab-Navigation
- Google Fonts werden weiterhin über Googles CDN geladen (kein eigenes Hosting), das ist
  in der Datenschutzerklärung entsprechend erklärt
