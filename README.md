# Werkia Userscript Icons

Ein zentraler Satz lesbarer Icons für Tampermonkey-Loader. Alle Dateien sind SVGs, damit sie in der Userscript-Liste und im Loader scharf bleiben.

## Einbindung

```javascript
// @iconURL      https://raw.githubusercontent.com/willywerkia/werkiaFavicons/main/KAM.svg
```

Bei neuen Scripts bitte das passende Kürzel als Dateiname verwenden. Für Werkzeuge ohne Fachbereich gibt es das Werkia-Favicon als `werkia-favicon.svg`.

Stil: flache Fläche in der Bereichsfarbe, weißes Kürzel in Arial Bold, keine Verläufe oder Symbole.

## Werkia

| Einsatz | Datei |
| --- | --- |
| Werkia-Favicon (Schraubenschlüssel), Fallback ohne Fachbereich | `werkia-favicon.svg`, `werkia-favicon.png` |
| Werkia-Logo (Schriftzug auf Weiß) | `werkia-logo.svg`, `werkia-logo.png` |

## PNG für Slack

Zu jedem SVG liegt ein PNG (512 × 512) mit gleichem Namen daneben, z. B. `KAM.png`. Die sind für Stellen, die kein SVG nehmen: Slack-Profilbilder (`icon_url`) und Custom-Emojis.

Nur als PNG gibt es die Profilbilder der VT-Bots im Slack: `VTA.png`, `VTV.png`, `VTS.png`. Quelle: `adminpanel/queries_bot/assets/` im OPS-Repo.

## Fachbereiche und Toolboxes

| Bereich | Datei |
| --- | --- |
| AGC Toolbox | `AGC.svg` |
| KAM Toolbox | `KAM.svg` |
| CEM Toolbox | `CEM.svg` |
| OBC Toolbox | `OBC.svg` |
| Sales Toolbox | `CS.svg` |
| OPS Übersicht | `OPS.svg` |

## OPS und Unterbereiche

| Bereich oder Funktion | Datei |
| --- | --- |
| EVA, Externer Vakanz-Assistent | `EVA.svg` |
| AP Toolbox | `AP.svg` |
| OM Toolbox und Matching | `OM.svg` |
| CV Parser und CV-Flows | `CV.svg` |
| Vakanzen und Bulk-Editoren | `VAK.svg` |
| Bulk-Arbeitgeber-Editor | `AG.svg` |
| Bulk-Vakanzen-Editor | `V.svg` |
| Portal-Uploads und Portal-Agenten | `PRT.svg` |
| Push Requests | `PR.svg` |

## Sales und Service

| Bereich oder Funktion | Datei |
| --- | --- |
| BA Job Extractor | `BA.svg` |
| Customer Success und Onboarding | `CS.svg` |

## Bestehende Kürzel

Diese Dateien ersetzen die alten, textlastigen Varianten, ohne die bestehenden Loader-URLs zu brechen: `VA.svg`, `BVA.svg` und `PU.svg`.
