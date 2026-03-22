# Swenja.Maria – Flyer

## Vorschau im Browser

Einfach `flyer.html` in Chrome oder Edge öffnen.

---

## Fotos einfügen

Im HTML-Code sind Platzhalter markiert. Jedes Foto-Feld enthält einen Kommentar:

```html
<!-- Foto hier einfügen: z.B. <img src="mein-foto.jpg" alt="Beschreibung"> -->
```

**Schritt 1:** Fotos in den `flyer/` Ordner kopieren (z.B. `foto1.jpg`)

**Schritt 2:** In `flyer.html` den Kommentar ersetzen:
```html
<img src="foto1.jpg" alt="Halsbänder" />
```

---

## Als PDF exportieren (für Canva-Import)

1. `flyer.html` in **Chrome** oder **Edge** öffnen
2. `Strg + P` (Drucken)
3. Drucker: **"Als PDF speichern"**
4. Einstellungen:
   - Papierformat: **A4**
   - Ränder: **Keine** (oder "Minimal")
   - Hintergrundgrafiken: **Aktiviert** ✓
5. Speichern

---

## In Canva importieren und nachbearbeiten

1. [canva.com](https://www.canva.com) öffnen
2. **"Design erstellen"** → **"Eigene Größe"** → 210 × 297 mm (A4)
3. **"Hochladen"** → die exportierte PDF-Datei auswählen
4. Das PDF wird als Bild importiert – nun können Elemente darüber gelegt werden
5. Fotos, Texte und Farben direkt in Canva anpassen

> **Tipp:** Alternativ kannst du in Canva direkt ein neues A4-Design anlegen und die Farben und Texte aus dem HTML-Flyer als Vorlage nutzen.

---

## Farbcodes (für Canva)

| Element         | Hex-Code  |
|----------------|-----------|
| Hintergrund    | `#f9f3fa` |
| Akzent/Lila    | `#c4a0c8` |
| Titelfarbe     | `#3a2a3e` |
| Textfarbe      | `#4a3550` |
| WhatsApp Grün  | `#25d366` |

## Schriften (für Canva)

- **Titel "Swenja.Maria"**: Cormorant Garamond (kostenlos auf Google Fonts)
- **Fließtext & Liste**: Lato Light / Lato Regular

---

## QR-Code

Der QR-Code verlinkt direkt auf WhatsApp: `https://wa.me/491707078106`

Dieser wird automatisch über einen externen Dienst generiert (Internet erforderlich).
Für den Offline-Druck empfiehlt sich ein eigener QR-Code via [qr.io](https://qr.io) oder [qrcode-monkey.com](https://www.qrcode-monkey.com/).
