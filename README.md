# Profil-Seite

![layout](drafts/page.png "Portfolio Seite")

- Seite nur für mobile
- meta Tag für die korrekte Skalierung auf Handys benutzen:
  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1">
  ```
- Link für Email, der E-Mail Anwendung öffnet (0/5)
```diff
- Das ist kein mailto-Link
```
- Link für Telefon, der Telefon-Anwendung öffnet (0/5)
- Link zum Lebenslauf(PDF), der einen Download auslöst (5/5)
- Links zu Social Media Profilen
  - Haben Icons der Dienste (10/10)
  - Sollen in einem neuen Tab öffnen (0/5)
```diff
- target blank fehlt
```
  
- Foto, das im Kreis dargestellt wird, mit border-radius (5/5)
```diff
- Bitte nicht !important verwenden.
```
- Navigation zu den Abschnitten mit Hash-Links (10/10)
- Bilder im Portfolio sollen verlinkt sein (10/10)

## Anforderungen für den Code
- Keine Block-Tags in Inline-Tags (10/10)
- Padding in den Links der Hauptnavigation (6/10)
```diff
- Es sollte auch padding an den anderen Seiten geben
```
- Abstand zwischen Text und Fensterrand und zwischen Text und Element-Rand (2/10)
```diff
- Kein Abstand zwischen Text und Fensterrand beim Portfolio-Abschnitt
- Kein Abstand zwischen den Links in Kontakt
- Kein Abstand beim Text in den Progress bars
```
- Korrekte html-Grundstruktur (html, head, body) (9/10)
```diff
- Bitte nicht br benutzen um Elemente untereinander anzuordnen
```
- Keine Viewport-Elemente im head (5/5)

### Punkte
(**72**/100)
